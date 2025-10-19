
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SIAM HASAN - The Sundarban</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background-color: #eaf4ec;
      color: #1e3d2f;
      text-align: center;
    }
    header {
      background: linear-gradient(120deg, #1e824c, #2ecc71);
      color: white;
      padding: 40px 20px;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }
    .images {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .images img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }
    .images img:hover {
      transform: scale(1.05);
    }
    .description {
      text-align: justify;
      margin-top: 20px;
      line-height: 1.7em;
      font-size: 1.05em;
    }
    footer {
      margin-top: 50px;
      padding: 20px;
      background: #1e824c;
      color: white;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SIAM HASAN</h1>
    <p>Roll: 875445</p>
  </header>

  <div class="container">
    <h2>The Sundarban</h2>
    <div class="images">
      <img src="sundarban1.jpg" alt="Boat on river in Sundarban">
      <img src="sundarban2.jpg" alt="Birds in Sundarban">
      <img src="sundarban3.jpg" alt="Deer in Sundarban forest">
      <img src="sundarban4.jpg" alt="Deer in Sundarban Animal">
    </div>

    <div class="description">
      <p>
        The Sundarban, often called the emerald crown of Bangladesh, is one of the most enchanting and mysterious places on Earth. Stretching over thousands of square kilometers along the Bay of Bengal, it is the largest mangrove forest in the world — a living masterpiece shaped by the rhythm of tides and time. Its beauty lies not only in its vastness but in its harmony, where the land, water, and sky merge in perfect balance. Countless rivers and creeks twist through emerald greenery, their reflections shimmering under the golden sunlight. The air carries the scent of salt and wildflowers, while the sounds of chirping birds and whispering winds weave together a melody of life.
      </p>
      <p>
        Home to the legendary Royal Bengal Tiger, spotted deer, crocodiles, and exotic birds, the Sundarban is a sanctuary of both serenity and strength. Here, danger and peace coexist — the calm of the forest always holding a hint of wild power. As dawn breaks, mist rises gently over the waterways, and as evening falls, the forest glows in soft amber light, painting a scene that feels almost unreal. For those who visit, the Sundarban offers more than a journey into nature — it is a journey into silence, awe, and connection. It reminds us that true beauty lies in simplicity, balance, and respect for the natural world — a living reminder that even the wildest places on Earth breathe with quiet grace and timeless wonder.
      </p>
    </div>

  </div>
<!-- Google Map Section -->
<!-- Google Map & Image Section -->
<h2>Google Map</h2>
<div class="map-section">
  <!-- বাম পাশে ছবি -->
  <div class="image-box">
    <img src="sundarban-photo.jpg" alt="sundarban-photo.jpg" />
    <p class="image-caption">The Royal Bengal Tiger</p>
    <p>The most aggressive Animal</p>
    <p>Sundarban, Bangladesh</p>
  </div>

  <!-- ডান পাশে ম্যাপ -->
  <div class="map-container">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d86087.74604733392!2d89.29738063951623!3d21.9484131340132!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a01ad003828a725%3A0x8de7bb23cb204815!2sSundarban%20(National%20Mangrove%20forest)%20Bangladesh!5e0!3m2!1sen!2sbd!4v1760852873363!5m2!1sen!2sbd"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
  </div>
</div>

<style>
  /* 📍 Google Map + Image Layout */
  .map-section {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 25px;
    margin: 40px auto;
    max-width: 1000px;
    flex-wrap: wrap; /* ছোট স্ক্রিনে একটার নিচে একটা আসবে */
  }

  /* 🖼️ বাম পাশের ছবির বক্স */
  .image-box {
    width: 100%;
    max-width: 400px;
    text-align: center;
  }

  .image-box img {
    width: 100%;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
  }

  .image-caption {
    margin-top: 10px;
    font-weight: 600;
    color: #1e3d2f;
    font-size: 1.1em;
  }

  /* 🗺️ ডান পাশের ম্যাপ */
  .map-container {
    width: 100%;
    max-width: 450px;
    aspect-ratio: 4 / 3;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  }

  .map-container iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }

  /* 📱 মোবাইল ভিউ এর জন্য */
  @media (max-width: 768px) {
    .map-section {
      flex-direction: column;
      align-items: center;
    }
    .image-box, .map-container {
      max-width: 90%;
    }
  }
</style>
    

  <footer>
    <p>© 2025 SIAM HASAN | Inspired by Nature</p>
  </footer>
</body>
</html>
