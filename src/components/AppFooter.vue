<!-- src/components/Footer.vue -->
<template>
  <footer class="bg-dark text-white py-4">
    <div class="container">
      <div class="row">
        <!-- Footer Column 1 -->
        <div class="col-md-4">
          <h5 class="text-uppercase">About Us</h5>
          <p>
            We are a company dedicated to providing the best services and products to our customers. 
            Follow us on our social media channels for the latest updates.
          </p>
        </div>
        <!-- Footer Column 2 -->
        <div class="col-md-4">
          <h5 class="text-uppercase">Quick Links</h5>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white">Home</a></li>
            <li><a href="#" class="text-white">About</a></li>
            <li><a href="#" class="text-white">Services</a></li>
            <li><a href="#" class="text-white">Contact</a></li>
          </ul>
        </div>
        <!-- Footer Column 3 -->
        <div class="col-md-4">
          <h5 class="text-uppercase">Follow Us</h5>
          <ul class="list-unstyled d-flex">
            <li class="mr-3">
              <a href="#" class="text-white"><i class="fab fa-facebook-f"></i></a>
            </li>
            <li class="mr-3">
              <a href="#" class="text-white"><i class="fab fa-twitter"></i></a>
            </li>
            <li class="mr-3">
              <a href="#" class="text-white"><i class="fab fa-instagram"></i></a>
            </li>
            <li>
              <a href="#" class="text-white"><i class="fab fa-linkedin-in"></i></a>
            </li>
          </ul>
        </div>
      </div>
      <!-- Footer Bottom -->
      <div class="text-center mt-4">
        <p class="mb-0">&copy; 2024 Your Company. All rights reserved.</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
}
</script>

<style scoped>
/* Scoped styles for Footer.vue */
footer {
  background-color: #343a40;
  position: fixed;
  bottom: 0;
  width: 100%;

}
footer a {
  text-decoration: none;
}
footer a:hover {
  text-decoration: underline;
}

</style>
