---
permalink: /About me/
layout: default
---

# About Me

Outside of my research, I enjoy playing squash, dancing, and cooking.

<div class="hobbies-container">
  <div class="hobby-item">
    <img src="{{ '/assets/images/IMG_4966.jpg' | relative_url }}" alt="Playing squash">
    <div class="hobby-content">
      <h3>Squash</h3>
      <p>I've been playing competitive squash for 5 years. It helps me stay active and focused.</p>
    </div>
  </div>
  
  <div class="hobby-item">
    <img src="{{ '/assets/images/IMG_8405.JPG' | relative_url }}" alt="Dancing">
    <div class="hobby-content">
      <h3>Dancing</h3>
      <p>From salsa to hip-hop, dancing is my creative outlet and stress reliever.</p>
    </div>
  </div>
  
  <div class="hobby-item">
    <img src="{{ '/assets/images/IMG_7515.JPG' | relative_url }}" alt="Cooking">
    <div class="hobby-content">
      <h3>Cooking</h3>
      <p>Experimenting with recipes from different cultures is one of my favorite weekend activities.</p>
    </div>
  </div>
</div>

<style>
.hobbies-container {
  max-width: 1000px;
  margin: 50px auto;
}

.hobby-item {
  display: flex;
  align-items: center;
  gap: 40px;
  margin-bottom: 60px;
}

.hobby-item:nth-child(even) {
  flex-direction: row-reverse;
}

.hobby-item img {
  width: 300px;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.hobby-content {
  flex: 1;
}

.hobby-content h3 {
  font-size: 1.8em;
  margin-bottom: 15px;
  color: #2c3e50;
}

.hobby-content p {
  font-size: 1.1em;
  line-height: 1.6;
  color: #555;
}

@media (max-width: 768px) {
  .hobby-item,
  .hobby-item:nth-child(even) {
    flex-direction: column;
    gap: 20px;
  }
  
  .hobby-item img {
    width: 100%;
    max-width: 400px;
  }
}
</style>
