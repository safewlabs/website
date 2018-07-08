<template>
  <div class="columns">
    <div class="column"></div>
    <div class="column content is-medium">
      <h1 class="title">{{ msg }}</h1>
      <b>Safew Tech Labs</b> is a boutique software development company. We develop high quality,
        well tested, high performing and scalable products for the web, Android and iOS. We are incredibly
        proud of our work and do not believe in taking half measures.
      <p>We are a group of global experts in design, development &amp; Ops. We're happy to work on related technologies if need be.
        We're constantly upskilling ourselves to remain on top of our game. Some of the technologies
        we can work with immediately are listed below.
      </p>
      <ul>
        <li>Ruby</li>
        <li>Rails</li>
        <li>PostgreSQl</li>
        <li>Elasticsearch</li>
        <li>Vue JS</li>
        <li>AWS and public cloud stack</li>
        <li>Serverless</li>
      </ul>
      <p>We are currently working on 2 products:</p>
      <ul>
        <li><a href="https://comix.life" target="blank">Comix</a> - A marketplace for Indie comics</li>
        <li><a href="https://getnotified.me" target="blank">Get Notified</a> - A full service notifications API.</li>
      </ul>
      <p>If you have any inquiries related to above projects or have any projects we can help with feel free to get in touch.</p>
      <p><a href="mailto:saurabh@safew.tech?subject=Howdy!" target="blank">Saurabh Bhatia</a>, Founder</p>
    </div>
    <div class="column"></div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Safew Tech Labs'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
