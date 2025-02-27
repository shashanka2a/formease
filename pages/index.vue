<template>
    <!-- Header -->
    <header id="navbar" class="bg-gradient-to-r shadow sticky-nav">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="text-xl font-bold">FormEase</a>
            <nav class="hidden md:flex space-x-6">
                <a href="#" class="nav-link hover:text-light-purple">Home</a>
                <a href="#" class="nav-link hover:text-light-purple">Features</a>
                <a href="#" class="nav-link hover:text-light-purple">Pricing</a>
                <a href="#" class="nav-link hover:text-light-purple">About</a>
                <a href="#" class="nav-link hover:text-light-purple">Contact</a>
            </nav>
            <div class="flex space-x-6">
                <a href="#" class="btn-signup bg-light-purple text-white px-4 py-2 rounded hover:bg-blue-secondary">Sign
                    Up</a>
                <a href="#" class="btn-login bg-gray-300 text-gray-800 px-4 py-2 rounded">Log In</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-light-purple text-white py-20">
        <div class="container mx-auto px-6 flex flex-col lg:flex-row items-center">
            <div class="lg:w-1/2 text-center lg:text-left mb-8 lg:mb-0">
                <h1 class="text-4xl font-bold mb-4">Create Forms with Ease</h1>
                <p class="text-lg mb-8">Simple, intuitive, and powerful form builder to streamline your data collection.
                </p>
                <a href="#"
                    class="bg-white text-purple-primary px-6 py-3 rounded hover:bg-blue-secondary hover:text-white">Get
                    Started for Free</a>
            </div>
            <div class="lg:w-1/2">
                <img src="~/assets/images/hero.png" alt="Hero Image" class="mx-auto w-full lg:w-3/4 h-auto">
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 bg-light-gray">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-8">Why Choose FormEase?</h2>
            <div class="flex flex-wrap -mx-4">
                <div class="w-full md:w-1/2 lg:w-1/4 px-4 mb-8">
                    <div
                        class="bg-white rounded-lg shadow p-6 h-full flex flex-col hover:shadow-lg transition-shadow duration-300 ease-in-out">
                        <img src="~/assets/images/drag_drop.png" alt="Drag and Drop" class="w-32 h-32 mx-auto mb-4">
                        <h3 class="text-xl font-bold mb-2">Drag and Drop Builder</h3>
                        <p class="flex-grow">Design forms effortlessly with our intuitive drag and drop interface.</p>
                    </div>
                </div>
                <div class="w-full md:w-1/2 lg:w-1/4 px-4 mb-8">
                    <div
                        class="bg-white rounded-lg shadow p-6 h-full flex flex-col hover:shadow-lg transition-shadow duration-300 ease-in-out">
                        <img src="~/assets/images/customize.png" alt="Customizable" class="w-32 h-32 mx-auto mb-4">
                        <h3 class="text-xl font-bold mb-2">Fully Customizable</h3>
                        <p class="flex-grow">Personalize your forms to match your brand and needs.</p>
                    </div>
                </div>
                <div class="w-full md:w-1/2 lg:w-1/4 px-4 mb-8">
                    <div
                        class="bg-white rounded-lg shadow p-6 h-full flex flex-col hover:shadow-lg transition-shadow duration-300 ease-in-out">
                        <img src="~/assets/images/api.png" alt="Integration" class="w-32 h-32 mx-auto mb-4">
                        <h3 class="text-xl font-bold mb-2">Seamless Integrations</h3>
                        <p class="flex-grow">Connect with popular tools like Google Sheets, Slack, and more.</p>
                    </div>
                </div>
                <div class="w-full md:w-1/2 lg:w-1/4 px-4 mb-8">
                    <div
                        class="bg-white rounded-lg shadow p-6 h-full flex flex-col hover:shadow-lg transition-shadow duration-300 ease-in-out">
                        <img src="~/assets/images/analytics.png" alt="Analytics" class="w-32 h-32 mx-auto mb-4">
                        <h3 class="text-xl font-bold mb-2">Real-Time Analytics</h3>
                        <p class="flex-grow">Get insights and make data-driven decisions with real-time analytics.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="bg-light-purple py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center text-white">How It Works</h2>
            <div class="relative">
                <!-- Vertical Line -->
                <div class="absolute inset-0 flex justify-center">
                    <div class="w-1 bg-gray-300"></div>
                </div>
                <!-- Step 1 -->
                <div class="relative flex flex-col items-center mb-8">
                    <div
                        class="flex items-center justify-center w-12 h-12 bg-white border-2 border-purple-primary rounded-full z-10 shadow-lg mb-4">
                        <span class="text-purple-primary font-bold text-lg">01</span>
                    </div>
                    <div
                        class="w-full max-w-md bg-white rounded-lg shadow-lg p-6 hover:bg-purple-100 transition duration-300 ease-in-out text-center">
                        <p>Sign up and create an account.</p>
                    </div>
                    <div class="w-1 bg-gray-300 h-8"></div>
                </div>
                <!-- Step 2 -->
                <div class="relative flex flex-col items-center mb-8">
                    <div
                        class="flex items-center justify-center w-12 h-12 bg-white border-2 border-purple-primary rounded-full z-10 shadow-lg mb-4">
                        <span class="text-purple-primary font-bold text-lg">02</span>
                    </div>
                    <div
                        class="w-full max-w-md bg-white rounded-lg shadow-lg p-6 hover:bg-purple-100 transition duration-300 ease-in-out text-center">
                        <p>Use the drag and drop builder to create your form.</p>
                    </div>
                    <div class="w-1 bg-gray-300 h-8"></div>
                </div>
                <!-- Step 3 -->
                <div class="relative flex flex-col items-center mb-8">
                    <div
                        class="flex items-center justify-center w-12 h-12 bg-white border-2 border-purple-primary rounded-full z-10 shadow-lg mb-4">
                        <span class="text-purple-primary font-bold text-lg">03</span>
                    </div>
                    <div
                        class="w-full max-w-md bg-white rounded-lg shadow-lg p-6 hover:bg-purple-100 transition duration-300 ease-in-out text-center">
                        <p>Customize and publish your form.</p>
                    </div>
                    <div class="w-1 bg-gray-300 h-8"></div>
                </div>
                <!-- Step 4 -->
                <div class="relative flex flex-col items-center">
                    <div
                        class="flex items-center justify-center w-12 h-12 bg-white border-2 border-purple-primary rounded-full z-10 shadow-lg mb-4">
                        <span class="text-purple-primary font-bold text-lg">04</span>
                    </div>
                    <div
                        class="w-full max-w-md bg-white rounded-lg shadow-lg p-6 hover:bg-purple-100 transition duration-300 ease-in-out text-center">
                        <p>Collect responses and analyze the data.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section
      <section class="py-20">
          <div class="container mx-auto px-6 text-center">
              <h2 class="text-3xl font-bold mb-8">What Our Users Say</h2>
              <div class="flex flex-wrap -mx-4">
                  <div class="w-full md:w-1/2 px-4 mb-8">
                      <div class="bg-white rounded shadow p-6">
                          <p class="mb-4">"FormEase has simplified our data collection process. It's user-friendly and integrates perfectly with our existing tools."</p>
                          <h4 class="text-xl font-bold">John Doe</h4>
                          <span>CEO, ExampleCorp</span>
                      </div>
                  </div>
                  <div class="w-full md:w-1/2 px-4 mb-8">
                      <div class="bg-white rounded shadow p-6">
                          <p class="mb-4">"The customization options are fantastic. We can design forms that truly represent our brand."</p>
                          <h4 class="text-xl font-bold">Jane Smith</h4>
                          <span>Marketing Manager, AnotherCo</span>
                      </div>
                  </div>
              </div>
          </div>
      </section>
       -->

    <!-- Pricing Section -->
    <section class="bg-light-gray py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center text-gray-800">Choose Your Plan</h2>
            <div class="flex flex-wrap justify-center">
                <div class="w-full md:w-1/3 lg:w-1/4 px-4 mb-8">
                    <div
                        class="relative bg-white rounded-lg shadow p-6 hover:shadow-lg transition-shadow duration-300 ease-in-out text-center">
                        <div class="absolute top-0 left-0 right-0 h-2 bg-blue-secondary rounded-t-lg"></div>
                        <h3 class="text-xl font-bold mb-4 text-purple-primary">Basic</h3>
                        <p class="text-3xl font-bold mb-4 text-gray-900">$10/month</p>
                        <ul class="mb-6 text-left list-disc list-inside">
                            <li class="mb-2">10 Forms</li>
                            <li class="mb-2">1000 Responses</li>
                            <li class="mb-2">Basic Support</li>
                        </ul>
                        <a href="#" class="bg-purple-primary text-white px-6 py-3 rounded hover:bg-blue-secondary">Sign
                            Up</a>
                    </div>
                </div>
                <div class="w-full md:w-1/3 lg:w-1/4 px-4 mb-8">
                    <div
                        class="relative bg-white rounded-lg shadow p-6 hover:shadow-lg transition-shadow duration-300 ease-in-out text-center">
                        <div class="absolute top-0 left-0 right-0 h-2 bg-blue-secondary rounded-t-lg"></div>
                        <h3 class="text-xl font-bold mb-4 text-purple-primary">Pro</h3>
                        <p class="text-3xl font-bold mb-4 text-gray-900">$25/month</p>
                        <ul class="mb-6 text-left list-disc list-inside">
                            <li class="mb-2">50 Forms</li>
                            <li class="mb-2">Unlimited Responses</li>
                            <li class="mb-2">Priority Support</li>
                        </ul>
                        <a href="#" class="bg-purple-primary text-white px-6 py-3 rounded hover:bg-blue-secondary">Sign
                            Up</a>
                    </div>
                </div>
                <div class="w-full md:w-1/3 lg:w-1/4 px-4 mb-8">
                    <div
                        class="relative bg-white rounded-lg shadow p-6 hover:shadow-lg transition-shadow duration-300 ease-in-out text-center">
                        <div class="absolute top-0 left-0 right-0 h-2 bg-blue-secondary rounded-t-lg"></div>
                        <h3 class="text-xl font-bold mb-4 text-purple-primary">Enterprise</h3>
                        <p class="text-3xl font-bold mb-4 text-gray-900">Contact Us</p>
                        <ul class="mb-6 text-left list-disc list-inside">
                            <li class="mb-2">Unlimited Forms</li>
                            <li class="mb-2">Unlimited Responses</li>
                            <li class="mb-2">Dedicated Support</li>
                        </ul>
                        <a href="#"
                            class="bg-purple-primary text-white px-6 py-3 rounded hover:bg-blue-secondary">Contact
                            Us</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-light-purple text-white py-10">
        <div class="container mx-auto px-6 text-center">
            <div class="mb-6">
                <img src="~/assets/images/logo.png" alt="FormEase Logo" class="mx-auto mb-4 w-32 h-auto">
                <p class="text-sm">Simplifying form creation for everyone.</p>
            </div>
            <div class="flex justify-center space-x-6 mb-6">
                <a href="#" class="hover:text-light-purple">Privacy Policy</a>
                <a href="#" class="hover:text-light-purple">Terms of Service</a>
                <a href="#" class="hover:text-light-purple">Contact Us</a>
            </div>
            <div class="text-sm">&copy; 2024 FormEase. All rights reserved.</div>
        </div>
    </footer>

</template>
