<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header class="topbar">
    <h1 class="logo">Gavvrrss</h1>

    <input type="checkbox" id="menu-toggle">
    <label for="menu-toggle" class="menu-icon">☰</label>
  </header>

  <aside class="sidebar">
    <ul>
      <li><a href="#intro">🏠 Home</a></li>
      <li><a href="#hobbies">🎯 Hobbies</a></li>
      <li><a href="#skills">💻 Skills</a></li>
      <li><a href="#gallery">📷 Gallery</a></li>
      <li><a href="#video">🎬 Video</a></li>
    </ul>
  </aside>

  <div class="mobile-topbar">
   <ul>
      <li><a href="#intro">Home</a></li>
      <li><a href="#hobbies"> Hobbies</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#video">Video</a></li>
   </ul>
  </div>

  <main class="content">

    <section id="intro" class="intro-section">
      <div class="intro-container">
        <img src="PROFILE_PICTURE.jpg" alt="Matt Gabriel Alforte profile picture" class="profile-pic">
        <h3>Matt Gabriel P. Alforte</h3>
        <p><strong>17</strong> years old and currently studying at <strong>University Of Nueva Caceres</strong>.</p>
        <p>In my free time, I enjoy <strong>Playing games and spending time with the love of my life</strong>.</p>
      </div>
    </section>

   <section id="hobbies" class="hobby-section">
    <h2>Hobbies</h2>
    <div class="hobby-container">
      <div class="hobby-card">
        <h3>Gaming</h3>
        <p>I like playing games</p>
      </div>
      <div class="hobby-card">
        <h3>Sleeping</h3>
        <p>I like sleeping.</p>
      </div>
      <div class="hobby-card">
        <h3>Eating</h3>
        <p>I like trying different foods.</p>
      </div>
      <div class="hobby-card">
        <h3>Love</h3>
        <p>I like loving the love of my life.</p>
      </div>
    </div>
  </section>

  <section id="skills" class="section">
      <div class="container">
        <h2>Skills</h2>
        <ul class="skills">
          <li>HTML <progress value="80" max="100"></progress></li>
          <li>CSS <progress value="70" max="100"></progress></li>
          <li>JavaScript <progress value="25" max="100"></progress></li>
        </ul>
      </div>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <p class="gallery-description">
        Every month, my partner and I make it a tradition to capture a special moment together in a photo booth. 
        These snapshots are little keepsakes of our journey, filled with laughter, love, and memories we’ll cherish forever.
      </p>
      <div class="gallery-grid">
        <div class="gallery-item">
          <img src="1st.jpg" alt="1st photo booth">
          <p>1st Photo Booth with the love of my life</p>
        </div>
        <div class="gallery-item">
          <img src="2nd.jpg" alt="2nd photo booth">
          <p>2nd Photo Booth and our 1st monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="3rd.jpg" alt="3rd photo booth">
          <p>3rd Photo Booth and our 2nd monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="4th.jpg" alt="4th photo booth">
          <p>4th Photo Booth and our 3rd monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="5th.jpg" alt="5th photo booth">
          <p>5th Photo Booth and our 4th monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="6th.jpg" alt="6th photo booth">
          <p>6th Photo Booth and our 5th monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="7th.jpg" alt="7th photo booth">
          <p>7th Photo Booth and our 6th monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="8th.jpg" alt="8th photo booth">
          <p>8th Photo Booth and our 7th monthsary</p>
        </div>
        <div class="gallery-item">
          <img src="SOON.avif" alt="coming soon">
          <p>Coming Soon...</p>
        </div>
      </div>
    </section>

    <section id="video">
      <h2>Video</h2>
      <p></p>
      <div class="video-container">
        <iframe 
          src="https://www.youtube.com/embed/X2YvvntQTls?list=RDX2YvvntQTls" 
          title="TVアニメ『薫る花は凛と咲く』ファーストPV" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
          referrerpolicy="strict-origin-when-cross-origin" 
          allowfullscreen>
        </iframe>
      </div>
    </section>

  </main>

</body>
<footer>
  <p>© 2025 Matt Gabriel P. Alforte. All rights reserved.</p>
</footer>
</html>
