<template>
  <div class="about-container">
    <center><h1>Moosic Social</h1></center>
    <div class="status-wrapper">
      <img src="../assets/band.png" alt="status" />
    </div>
    <h3>What is this?</h3>
    <p class="first-parg">Is a Social Platform made by Musicians for Musicians.</p>
	<pre>    </pre>
    <p>
      Music is the stings that keep this world circulating. Music defines cultures and people. Whether you sing, play an instrument or even want to learn, MOOSIC is the Social Platform for you. 
    </p>
    <h3>What can You do?</h3>
    <div class="what-can">
      <div class="image">
        <img class="question" src="../assets/question.jpg" alt="question" />
      </div>
      <div class="words">
        <h4>As a Musician -</h4>
        <ul>
			<li>Can you Sing?</li>
			<li>Can you play an Instrument?</li>
			<li>Can you Produce ?</li>
			<li>Can you Mix music? DJ STYLE? </li>
        </ul>
        <h4>As Someone who wants to learn -</h4>
        <ul>
          <li>You can learn to sing</li>
          <li>You can create new Music Ideas</li>
          <li>You can write your own songs</li>
          <li>You can learn an instrument</li>
          <li>You can learn to mix music DJ STYLE</li>
          <li>You can learn to produce music</li>
          <li>You can get advice from muscians</li>
          
        </ul>
      </div>
    </div>
	<pre>     </pre>
	<pre>     </pre>
	<pre>     </pre>
    <p>@2020 : THIS IS A FINAL PROJECT, UWI STA, INFO 1601, MR. MENDEZ</p>
    <section class="src">
		<p>Group Memebers:</p>
		<ul>
		<li>Daniel Rasheed</li>
		<li>Tariq Mohammed</li>
		<li>Michael Tan</li>
		<li>Pradeep Mahabir</li>
      </ul>
    </section>
  </div>
</template>
<style scoped>
.about-container {
  background: white;
  margin-top: 50px;
  padding: 50px 20px;
  min-height: 100vh;
  margin-bottom: auto;
}
h1 {
  margin-bottom: 20px;
}
h3 {
  margin: 10px 0;
}
h4 {
  margin-left: 30px;
  color: #41b883;
}
ul {
  padding: 5px 50px;
}
li {
  margin: 10px 0;
}
.question{
	height: 400px;
	width: 80px;
	}

.src {
  margin-top: 100px;
  display: flex;
  justify-content: center;
  width: 100%;
}
.status-wrapper {
  display: flex;
  justify-content: center;
}
.status {
  width: 1920px;
  height: 1080px;
}
.what-can {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.what-can .image img {
  width: 100%;
}
.technology {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.technology img {
  width: 100%;
  height: 300px;
}
</style>
