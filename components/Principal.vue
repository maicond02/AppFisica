<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 98.3%; max-width: 98.3%; min-height: 80vh;">
            <template #title>

            </template>
            <template #content>
                <div class="grid">
                    <div class="col">
                        <div class="card">
                            <header class="card-header">
                            <p>Maio de 2023</p>
                            <span class="title">Aulas gravadas</span>
                            </header>
                            <div class="card-author">
                            <a class="author-avatar" href="#">
                                <span>
                            </span></a>
                            <svg class="half-circle" viewBox="0 0 106 57">
                                <path d="M102 4c0 27.1-21.9 49-49 49S4 31.1 4 4"></path>
                            </svg>
                            <div class="author-name">
                                <div class="author-name-prefix">Author</div> Professor M.A
                                </div>
                            </div>
                            <div class="tags">
                                <a href="#">Física 1</a>
                                <a href="#">Física 2</a>
                                <a href="#">Física 3</a>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <header class="card-header">
                            <p>Maio de 2023</p>
                            <span class="title">Aulas ao vivo</span>
                            </header>
                            <div class="card-author">
                            <a class="author-avatar" href="#">
                                <span>
                            </span></a>
                            <svg class="half-circle" viewBox="0 0 106 57">
                                <path d="M102 4c0 27.1-21.9 49-49 49S4 31.1 4 4"></path>
                            </svg>
                            <div class="author-name">
                                <div class="author-name-prefix">Author</div> M.A
                                </div>
                            </div>
                            <div class="tags">
                                <a href="#">Física 1</a>
                                <a href="#">Física 2</a>
                                <a href="#">Física 3</a>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <header class="card-header">
                            <p>Maio de 2023</p>
                            <span class="title">Materiais</span>
                            </header>
                            <div class="card-author">
                            <a class="author-avatar" href="#">
                                <span>
                            </span></a>
                            <svg class="half-circle" viewBox="0 0 106 57">
                                <path d="M102 4c0 27.1-21.9 49-49 49S4 31.1 4 4"></path>
                            </svg>
                            <div class="author-name">
                                <div class="author-name-prefix">Author</div> M.A
                                </div>
                            </div>
                            <div class="tags">
                                <a href="#">Física 1</a>
                                <a href="#">Física 2</a>
                                <a href="#">Física 3</a>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <header class="card-header">
                            <p>Maio de 2023</p>
                            <span class="title">Fórum</span>
                            </header>
                            <div class="card-author">
                            <a class="author-avatar" href="#">
                                <span>
                            </span></a>
                            <svg class="half-circle" viewBox="0 0 106 57">
                                <path d="M102 4c0 27.1-21.9 49-49 49S4 31.1 4 4"></path>
                            </svg>
                            <div class="author-name">
                                <div class="author-name-prefix"></div>
                                </div>
                            </div>
                            <div class="tags">
                                <a href="#">Física 1</a>
                                <a href="#">Física 2</a>
                                <a href="#">Física 3</a>
                            </div>
                        </div>
                    </div>
                </div>
            </template>
        </Card>
    </div>
</template>

<script>

</script>

<style scoped>
    .p-card{
        background-color: rgba(255, 255, 255, 0.089)
    }
    .p-button{
        color: white !important;
    }

    a{
        text-decoration: none !important;
    }
    .card {
    display: flex;
    position: relative;
    flex-direction: column;
    height: 350px;
    width: 190px;
    min-width: 250px;
    padding: 1rem;
    border-radius: 16px;
    background: #2c2d35;
    box-shadow: -1rem 0 3rem #002f4667;
    transition: .2s;
    font-family: 'Inter', sans-serif;
}

.card:hover {
  transform: translateY(-0.4rem);
}

.card-author {
  position: relative;
  display: grid;
  grid-template-columns: 75px 1fr;
  align-items: center;
  margin: 3rem 0 0;
}

.author-name {
  color: #7a7a8c;
}

.author-name-prefix {
  color: #7a7a8c;
  font-weight: 600;
}

.author-avatar span {
  display: block;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: #f2f2f2;
  margin: 16px 10px;
}

.half-circle {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 60px;
  height: 48px;
  fill: none;
  stroke: #00fbff;
  stroke-width: 8;
  stroke-linecap: round;
}

.card-header {
  margin-bottom: auto;
  color: #7a7a8c;
}

.card-header p {
  font-size: 14px;
  margin: 0 0 1rem;
  color: #7a7a8c;
}

.card-header .title {
  font-size: 25px;
  margin: .25rem 0 auto;
  cursor: pointer;
  font-family: 'Arial Black', sans-serif;
}

.card-header .title:hover {
  background: linear-gradient(90deg,#00fff7,#008cff);
  text-shadow: none;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.tags {
  margin: 1rem 0 2rem;
  padding: .5rem 0 1rem;
  line-height: 2;
  margin-bottom: 0;
}

.tags a {
  font-style: normal;
  font-weight: 700;
  color: #7a7a8c;
  text-transform: uppercase;
  font-size: .66rem;
  border: 3px solid #7a7a8c;
  border-radius: 2rem;
  padding: .2rem .85rem .25rem;
  position: relative;
}

.tags a:hover {
  background: linear-gradient(90deg,#00fff7,#008cff);
  text-shadow: none;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-box-decoration-break: clone;
  box-decoration-break: clone;
  background-clip: text;
  border-color: white;
}
</style>