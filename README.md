<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Aeo Records LLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background: #070707;
      color: #f5f5f5;
    }

    header {
      background: linear-gradient(to bottom, rgba(0,0,0,0.7), #070707),
                  url("https://images.unsplash.com/photo-1511379938547-c1f69419868d") center/cover;
      padding: 120px 20px;
      text-align: center;
      border-bottom: 1px solid #1e1e1e;
    }

    header h1 {
      font-size: 3.4rem;
      margin: 0;
      letter-spacing: 4px;
      text-transform: uppercase;
    }

    header p {
      margin-top: 18px;
      font-size: 1.25rem;
      color: #c9a3ff;
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 80px 20px;
    }

    h2 {
      font-size: 2.4rem;
      margin-bottom: 40px;
      color: #b388ff;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .label-statement {
      font-size: 1.15rem;
      max-width: 850px;
      line-height: 1.8;
      color: #ddd;
    }

    .artist-hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: center;
    }

    .artist-info h3 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    .artist-info span {
      color: #b388ff;
      font-size: 1rem;
      letter-spacing: 1px;
    }

    .artist-info p {
      margin-top: 20px;
      line-height: 1.7;
      color: #ddd;
    }

    .artist-links a {
      display: inline-block;
      margin-top: 20px;
      margin-right: 15px;
      padding: 12px 24px;
      border-radius: 30px;
      border: 1px solid #b388ff;
      color: #b388ff;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .artist-links a:hover {
      background: #b388ff;
      color: #000;
    }

    .embed-box {
      background: #0f0f0f;
      padding: 25px;
      border-radius: 15px;
      border: 1px solid #262626;
      box-shadow: 0 0 35px rgba(155,0,255,0.15);
    }

    iframe {
      width: 100%;
      border-radius: 12px;
    }

    .submit-box {

