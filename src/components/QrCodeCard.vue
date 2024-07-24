<template>
  <div class="qr-code-card">
    <section>
      <img src="@/assets/images/qr-code.png" alt="QR code">
    </section>
    
    <section class="description-section">
      <h1 class="heading">Improve your front-end skills by building projects</h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </section>
  </div>
</template>

<style scoped lang="scss">
.qr-code-card {
  --padding: var(--spacing-200);
  --inner-border-radius: 10px;
  
  max-width: 320px;
  padding: var(--padding);
  background-color: var(--color-white);
  border-radius: calc(var(--inner-border-radius) + var(--padding));
  
  img {
    border-radius: var(--inner-border-radius);
  }
  
  .description-section {
    margin-block: var(--spacing-300);
    text-align: center;
    
    .heading {
      color: var(--color-slate-900);
      font-size: 1.375rem;
      line-height: 1.2;
    }
    
    p {
      margin-top: var(--spacing-200);
      color: var(--color-slate-500);
      font-size: 0.9375rem;
      line-height: 1.4;
      letter-spacing: 0.2px;
    }
  }
}
</style>
