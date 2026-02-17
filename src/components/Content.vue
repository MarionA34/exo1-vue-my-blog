<script setup></script>

<template>
  <div class="container">
    <h1>An awesome title</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit.
      <span>Asperiores ducimus obcaecati</span> velit natus ex nesciunt fugit in maiores dicta,
      consequuntur ut porro, quod omnis earum vel iste aspernatur dolor. Amet. Ex necessitatibus
      dignissimos fugiat unde ducimus expedita laborum rem quos iure recusandae. Minima officia non,
      error magnam cumque provident itaque quis molestias consequuntur assumenda ex porro iure
      maxime praesentium autem. Iste provident tenetur fugit aperiam molestiae illo eos, nesciunt
      dolor cumque accusamus esse et, est asperiores dolores aliquid corrupti
      <span>quas velit repellat amet quos?</span> Officiis magni deleniti corporis repellat minima.
      Doloremque id voluptas ab pariatur placeat quae vero saepe aspernatur corrupti, quos similique
      alias veritatis blanditiis officia nobis ratione perspiciatis ea nesciunt quaerat et sapiente?
      Numquam quo sit perferendis laboriosam?
    </p>
    <br />
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores ducimus obcaecati velit
      natus ex nesciunt fugit in maiores dicta, consequuntur ut porro, quod omnis earum vel iste
      aspernatur dolor. Amet. Ex necessitatibus dignissimos fugiat unde
      <span>ducimus expedita laborum</span> rem quos iure recusandae. Minima officia non, error
      magnam cumque provident itaque quis molestias consequuntur assumenda ex porro iure maxime
      praesentium autem. Iste provident tenetur fugit aperiam molestiae illo eos, nesciunt dolor
      cumque accusamus esse et, est asperiores dolores aliquid corrupti quas velit repellat amet
      quos? Officiis magni deleniti corporis repellat minima. Doloremque id voluptas ab pariatur
      placeat quae vero <span>saepe aspernatur corrupti</span>, quos similique alias veritatis
      blanditiis officia nobis ratione perspiciatis ea nesciunt quaerat et sapiente? Numquam quo sit
      perferendis laboriosam?
    </p>
  </div>
</template>

<style scoped>
div {
  height: calc(100vh - var(--footer-height) - var(--header-height));
}

h1 {
  text-decoration: underline;
  text-decoration-color: var(--main-yellow);
  margin-top: 30px;
  margin-bottom: 20px;
}

span {
  color: var(--main-yellow);
}
</style>
