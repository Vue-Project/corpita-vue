<template>
  <header id="main-header" >
    <nav class="navbar navbar-expand-lg navbar-dark" >
      <div class="container">
    
        <!-- Brand -->
				<NuxtLink class="navbar-brand" to="/">
          	<img src="~/assets/images/logo.png" class="navbar-brand-img" alt="Corptia Logo">
				</NuxtLink>

        <!-- Toggler -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
    
        <!-- Collapse -->
        <div class="collapse navbar-collapse" id="navbarCollapse">
    
          <!-- Toggler -->
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <i class="fe fe-x"></i>
          </button>
    
          <!-- Navigation -->
          <ul class="navbar-nav m-auto">

            <li class="nav-item ">
              <!-- <a class="nav-link" href="/" aria-haspopup="true" aria-expanded="false">
                Home
              </a> -->
							<NuxtLink class="nav-link" to="/">Home</NuxtLink>

            </li>
            <li class="nav-item ">
              <!-- <a class="nav-link"  href="/company.html" aria-haspopup="true" aria-expanded="false">
                Company
              </a> -->
							<NuxtLink class="nav-link" to="/company">Company</NuxtLink>

            </li>
            <li class="nav-item ">
              <!-- <a class="nav-link" href="/services.html" aria-haspopup="true" aria-expanded="false">
                Services
              </a> -->
							<NuxtLink class="nav-link" to="/services">Services</NuxtLink>
            </li>
            <li class="nav-item ">
              <!-- <a class="nav-link" href="/works.html" aria-haspopup="true" aria-expanded="false">
                Works
              </a> -->
         			<NuxtLink class="nav-link" to="/works">Works</NuxtLink>
            </li>
            <li class="nav-item ">
              <!-- <a class="nav-link" id="navbarLandings"  href="/blog.html" aria-haspopup="true" aria-expanded="false">
                Blog
              </a> -->
							<NuxtLink class="nav-link" to="/blog">Blog</NuxtLink>
            </li>
            <li class="nav-item ">
              <!-- <a class="nav-link" id="navbarLandings"  href="/contact.html" aria-haspopup="true" aria-expanded="false">
                Contact Us
              </a> -->
							<NuxtLink class="nav-link" to="/contact">Contact US</NuxtLink>
            </li>
          </ul>
    
            <!-- SocialMedia -->
            <SocialMedia />
    
        </div>
    
      </div>
    </nav>
  </header>
	
</template>

<script>
export default {
	 name: 'NavDark',
   layout:'component',

	 
	 
}
</script>


<style>

</style>