<script>
    let { children } = $props();
    import smxlogo from '$lib/images/logo/smx.png'
    import fblogo from '$lib/images/social/facebook.png'
    import linkedinlogo from '$lib/images/social/linkedin.png'
    import githublogo from '$lib/images/social/github.png'
</script>
<nav class="fixed  top-0 left-0 w-full h-20  m-auto place-items-center  z-50 bg-[#003347]">
    <div class=" mx-auto flex justify-between items-center h-full px-6">
        <!-- LOGO -->
        <a href="/" class="w-12 border-b-4 border-green-500">
            <img src={smxlogo} alt="smx logo" class="object-cover object-center border-b-2 border-green-600">
        </a>

        <!-- NAV LINKS -->
        <ul class="flex gap-16 text-white font-bold">
            <li><a href="/home" class="hover:text-green-600 ">Home</a></li>
            <li><a href="/home/products" class="hover:text-green-600 ">Products</a></li>
            <li><a href="/home/services" class="hover:text-green-600 ">Services</a></li>
            <li><a href="/home/resources" class="hover:text-green-600 ">Resources</a></li>
            <li><a href="/home/contact" class="hover:text-green-600 ">Contact</a></li>
        </ul>

        <!-- SOCIAL LINKS -->
        <ul class="flex gap-4 ">
            <li>
                <a href="https://www.facebook.com/smrtmrktx" target="_blank"
                    class="w-8 h-8 grid place-items-center bg-white  rounded-lg hover:shadow-lg">
                    <img src={fblogo} alt="facebook logo" class="object-cover object-center">
                </a>
            </li>
            <li>
                <a href="https://linkedin.com/company/smrtmrktx/" target="_blank"
                    class="w-8 h-8 grid place-items-center bg-white  rounded-lg hover:shadow-lg">
                    <img src={linkedinlogo} alt="linkedin logo" class="object-cover object-center">
                </a>
            </li>
            <li>
                <a href="https://github.com/SmrtMrktX" target="_blank"
                    class="w-8 h-8 grid place-items-center bg-white rounded-lg hover:shadow-lg">
                    <img src={githublogo} alt="github logo" class="object-cover object-center">
               </a>
            </li>
        </ul>

        <!-- TOGGLE BUTTONS -->
        
    </div>
</nav>
<div class="mt-20">
      {@render children()}
</div>
