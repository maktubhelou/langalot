<template>
  <div class="page">
    <!-- Navigation -->
    <nav id="topnav" class="grid">
      <ul>
        <a href="#topnav"><li class="nav-item">Home</li></a>
        <a href="#section-a"><li class="nav-item">About</li></a>
        <a href="#section-b"><li class="nav-item">Details</li></a>
        <a href="#section-d"><li class="nav-item">Contact</li></a>
      </ul>
    </nav>

    <!-- Header Showcase -->
    <header id="showcase" class="grid">
      <div class="bg-image"></div>
      <div class="content-wrap">
        <h1>Welcome to Langalot</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias commodi est veniam sit veritatis nihil cupiditate officia voluptatem possimus repellendus.</p>
        <a href="#section-b" class="btn">Read More</a>
      </div>
    </header>

    <!-- Main Area  -->
    <main id="main">
      <!-- Section A -->
      <section id="section-a" class="grid">
        <div class="content-wrap">
          <h2 class="content-title">A Community of Polyglots</h2>
          <div class="content-text">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt, adipisci nemo soluta cum doloribus ducimus, quisquam officia quod assumenda dolor corrupti, commodi possimus sit laboriosam laudantium nulla in. Iure voluptas sint esse placeat, corporis voluptatibus quam? Possimus quaerat unde esse?</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Velit ad unde dolorum culpa eaque ipsa corrupti iusto enim voluptatum necessitatibus accusamus quos doloribus, tempora ducimus maxime distinctio? Accusantium, laudantium, facere laborum maiores velit sunt vel, adipisci in exercitationem deserunt perferendis omnis! Vel corrupti eum consequatur voluptas accusamus tempora rerum dolorum!</p>
          </div>
        </div>
      </section>
      <!-- Section B -->
      <section id="section-b" class="grid">
        <ul>
          <li>
            <div class="card">
              <img src="@/assets/img/connect.png" alt="connect">
              <div class="card-content">
                <h3 class="card-title">Connect</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi pariatur nihil incidunt deleniti at cupiditate sapiente, aliquid atque corporis sit?</p>
              </div>
            </div>
          </li>
          <li>
            <div class="card">
              <img src="@/assets/img/share.png" alt="share">
              <div class="card-content">
                <h3 class="card-title">Share</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi pariatur nihil incidunt deleniti at cupiditate sapiente, aliquid atque corporis sit?</p>
              </div>
            </div>
          </li>
          <li>
            <div class="card">
              <img src="@/assets/img/grow.png" alt="grow">
              <div class="card-content">
                <h3 class="card-title">Grow</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi pariatur nihil incidunt deleniti at cupiditate sapiente, aliquid atque corporis sit?</p>
              </div>
            </div>
          </li>
        </ul>
      </section>

      <!-- Section C -->
      <section id="section-c" class="grid">
        <div class="content-wrap">
          <h2 class="content-title">We make learning language social</h2>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut laborum debitis eos ea pariatur dolorem officia praesentium aliquid in esse exercitationem ratione, veritatis saepe ab earum perferendis, nam, iusto voluptatum.</p>
        </div>
      </section>

      <!-- Section D -->
      <section id="section-d" class="grid">
        <div class="box">
          <h2 class="content-title">Contact Us</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis animi reprehenderit maiores consequatur autem vero ea impedit, fuga error dignissimos.</p>
          <p>contact@markevans.co</p>
        </div>
        <div class="box">
          <h2 class="content-title">About Our Mission</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo atque beatae neque impedit! Sequi doloremque provident placeat necessitatibus magnam reprehenderit?</p>
        </div>
      </section>

    </main>

    <!-- Footer -->
    <footer id="main-footer" class="grid">
      <div>&copy; Langalot</div>
      <div>Project By <a href="http://www.markevans.co" target="_blank">Mark Evans</a></div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
