<template>
  <div class="hero">
    <div class="hero__container container">
      <div class="hero__image">
        <img src="../img/imagen-personal.png" alt="image">
      </div>
      <div class="hero__text">
        <h1 class="hero__title">Miguel Ruz</h1>
        <p class="hero__description">
          Soy Diseñador UI, actualmente vivo en Turbaco-Bolivar, un pueblo a las afueras de Cartagena (Colombia).
          <br> <br>
          Me agrada la idea de trabajar en equipo, pienso que es una manera de conectar con nuevas habilidades y de brindar mi conocimiento al equipo con el fin de mejorar la productividad en el desarrollo de algun producto digital. Me gusta descubrir cosas nuevas a diario y ser un activo valioso en cualquier equipo en el que me desarrolle, por lo que estoy aprendiendo constantemente e investigando acerca de las nuevas tendencias.
          <br> <br>
          Trato de buscar todo el Feedback posible en los proyectos, con el fin de mejorar y poder hacer diseños que no solo sean atractivos esteticamente sino que sean accesibles y funcionales por lo que me gusta trabajar muy de la mano con los stakeholders.
          Hablemos! <br> <br>
          <a href="#" class="hero__link">
            miguelruz1126@gmail.com
          </a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroComponent'
}
</script>

<style>
.hero {
  margin: 32px 0 64px;
}

.hero__container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.hero__image {
  width: 100%;
  height: 401px;
  border-radius: 8px;
  overflow: hidden;
}

.hero__image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hero__title {
  margin: 24px 0;
}

.hero__link {
  text-decoration: none;
  cursor: pointer;
  color: #5C62EC;
}

.hero__link:hover {
  color: #FFFFFF;
}

@media only screen and (min-width: 760px) {
  .hero__image {
    height: 547px;
  }
}

@media only screen and (min-width: 1200px) {
  .hero {
    margin: 64px 0 128px;
  }

  .hero__container {
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
  }

  .hero__image {
    max-width: 448px;
    height: 547px;
    margin-bottom: 0;
  }

  .hero__title {
    margin: 0 0 24px 0;
  }

  .hero__text {
    flex: 1;
    max-width: 568px;
  }
}
</style>
