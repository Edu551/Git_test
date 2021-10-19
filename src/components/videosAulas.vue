<template>
  <div class="container">
    <div class="videoAulas">
      <img src="../assets/images/imagemVideo.svg" alt="Imagem" />
      <div>
        <h3>Aula 1</h3>

        <p>
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut
          fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem
          sequi nesciunt. Ipsam voluptatem quia voluptas sit aspernatur aut odit
          aut fugit, sed quia consequuntur magni dolores eos qui ratione
          voluptatem sequi nesciunt.
        </p>
      </div>
    </div>

    <hr />

    <div class="videoAulas">
      <img src="../assets/images/imagemVideo.svg" alt="Imagem" />
      <div>
        <h3>Aula 1</h3>
        <p>
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut
          fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem
          sequi nesciunt. Ipsam voluptatem quia voluptas sit aspernatur aut odit
          aut fugit, sed quia consequuntur magni dolores eos qui ratione
          voluptatem sequi nesciunt.
        </p>
      </div>
    </div>

    <hr />

    <div class="videoAulas">
      <img src="../assets/images/imagemVideo.svg" alt="Imagem" />
      <div>
        <h3>Aula 1</h3>

        <p>
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut
          fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem
          sequi nesciunt. Ipsam voluptatem quia voluptas sit aspernatur aut odit
          aut fugit, sed quia consequuntur magni dolores eos qui ratione
          voluptatem sequi nesciunt.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Videos Aulas",
};
</script>

<style scoped>
.container {
  flex-wrap: wrap;
  background: #f7f7f7;
}

.videoAulas {
  display: flex;
  margin-top: 81px;
}
.videoAulas img {
  margin: 75px 76px 0px 213px;
  max-width: 462px;
  max-height: 261px;
}
.videoAulas h3 {
  margin: 75px 0px 26px 0px;

  font-family: Ubuntu;
  font-style: normal;
  font-weight: bold;
  font-size: 35px;
  line-height: 40px;

  color: #ff4081;
}
.videoAulas p {
  margin: 26px 188px 73px 0px;
  max-width: 501px;
  height: 195px;

  font-family: Ubuntu;
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 23px;
  display: flex;
  align-items: center;

  color: #000000;
}

hr {
  margin: 0px 98px 0px 98px;
  max-width: 1244px;
  height: 3px;

  background: #c4c4c4;
}
</style>
