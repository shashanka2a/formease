<template>
  <NuxtPage />
</template>

<script>
onMounted(() => {
  document.body.classList.add('bg-light-gray');

  document.querySelectorAll('.feature-card').forEach(card => {
    card.addEventListener('mouseover', () => {
      card.classList.add('shadow-2xl');
    });
    card.addEventListener('mouseout', () => {
      card.classList.remove('shadow-2xl');
    });
  });
  document.querySelectorAll('.hover\\:bg-purple-100').forEach((element) => {
    element.addEventListener('mouseover', () => {
      element.classList.add('bg-purple-100');
    });
    element.addEventListener('mouseout', () => {
      element.classList.remove('bg-purple-100');
    });
  });
  // Change navbar style on scroll
  window.onscroll = function () {
    const navbar = document.getElementById('navbar');
    if (window.scrollY > 50) {
      navbar.classList.add('scrolled');
    } else {
      navbar.classList.remove('scrolled');
    }
  };

})
</script>

<style>
.bg-purple-primary {
  background-color: #6C63FF;
}

.text-purple-primary {
  color: #6C63FF;
}

.hover\:bg-purple-primary:hover {
  background-color: #6C63FF;
}

.hover\:text-purple-primary:hover {
  color: #6C63FF;
}

.bg-blue-secondary {
  background-color: #3F3D56;
}

.text-blue-secondary {
  color: #3F3D56;
}

.hover\:bg-blue-secondary:hover {
  background-color: #3F3D56;
}

.hover\:text-blue-secondary:hover {
  color: #3F3D56;
}

.bg-light-purple {
  background-color: #A29BFE;
}

.bg-light-gray {
  background-color: #F3F4F6;
}

.rounded-lg {
  border-radius: 1rem;
  /* Adjust the radius as needed */
}
</style>
