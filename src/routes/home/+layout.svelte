<script>
    let { children } = $props();
    import smxlogo from '$lib/images/logo/smx.png'
    import fblogo from '$lib/images/social/facebook.png'
    import linkedinlogo from '$lib/images/social/linkedin.png'
    import githublogo from '$lib/images/social/github.png'
</script>
<nav class="fixed  top-0 left-0 w-full h-20  m-auto place-items-center  z-50 ">
    <div class=" mx-auto flex justify-between items-center h-full px-6 backdrop-blur-sm  bg-transparent dark:backdrop-blur-sm	 dark:bg-transparent shadow-md ">
        <!-- LOGO -->
        <a href="/" class="w-12 border-b-4 border-green-500">
            <img src={smxlogo} alt="smx logo" class="object-cover object-center border-b-2 border-green-600">
        </a>

        <!-- NAV LINKS -->
        <ul class="flex gap-16 font-bold ">
            <li><a href="/home" class=" "><svg class="w-6 h-6 text-gray-800 dark:text-white hover:text-green-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m4 12 8-8 8 8M6 10.5V19a1 1 0 0 0 1 1h3v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a1 1 0 0 0 1-1v-8.5"/>
              </svg></a></li>
            <li><a href="/home/products" class=" "><svg class="w-6 h-6 text-gray-800 dark:text-white hover:text-green-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 16H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v1M9 12H4m8 8V9h8v11h-8Zm0 0H9m8-4a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/>
              </svg>
              </a></li>
            <li><a href="/home/services" class=" "><svg class="w-6 h-6 text-gray-800 dark:text-white hover:text-green-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7H5a2 2 0 0 0-2 2v4m5-6h8M8 7V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2m0 0h3a2 2 0 0 1 2 2v4m0 0v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-6m18 0s-4 2-9 2-9-2-9-2m9-2h.01"/>
              </svg>
              
              </a></li>
            <li><a href="/home/resources" class=" "><svg class="w-6 h-6 text-gray-800 dark:text-white hover:text-green-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 8v8m0-8a2 2 0 1 0 0-4 2 2 0 0 0 0 4Zm0 8a2 2 0 1 0 0 4 2 2 0 0 0 0-4Zm6-2a2 2 0 1 1 4 0 2 2 0 0 1-4 0Zm0 0h-1a5 5 0 0 1-5-5v-.5"/>
              </svg>
              </a></li>
            <li><a href="/home/contact" class=" "><svg class="w-6 h-6 text-gray-800 dark:text-white hover:text-green-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 6H5m2 3H5m2 3H5m2 3H5m2 3H5m11-1a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2M7 3h11a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm8 7a2 2 0 1 1-4 0 2 2 0 0 1 4 0Z"/>
              </svg>
              </a></li>
        </ul>

        <!-- SOCIAL LINKS -->
        <ul class="flex gap-4 ">
            <li>
                <a href="https://www.facebook.com/smrtmrktx" target="_blank"
                    class="w-8 h-8 grid place-items-center rounded-full hover:shadow-lg">
                    <img src={fblogo} alt="facebook logo" class="object-cover object-center">
                </a>
            </li>
            <li>
                <a href="https://linkedin.com/company/smrtmrktx/" target="_blank"
                    class="w-8 h-8 grid place-items-center rounded-full hover:shadow-lg">
                    <img src={linkedinlogo} alt="linkedin logo" class="object-cover object-center">
                </a>
            </li>
            <li>
                <a href="https://github.com/SmrtMrktX" target="_blank"
                    class="w-8 h-8 grid place-items-center rounded-full hover:shadow-lg ">
                    <img src={githublogo} alt="github logo" class="object-cover object-center">
               </a>
            </li>
        </ul>

        
    </div>
</nav>
<div class="mt-20">
      {@render children()}
</div>
