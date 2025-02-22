---
layout: base 
title: Gamify
description: 
permalink: /gamify
---

<div class="toolkit-buttons">
  <a href="{{site.baseurl}}/gamify/adventureGame" class="toolkit-button" data-description="This page contains all the games developed by CSA. It includes an adventure game where you can explore endless opurtunites. Within this game you can learn how to gamble by playing the gambling game or all about stocks and crypto in our investment game!" data-authors="Author: NITD+People">
    <img src="{{site.baseurl}}/images/toolkit-nav-buttons/adventure.png" alt="Gamify" />
    <span class="button-name">Gamify</span>
    <div class="description">
      <p>This page contains all the games developed by CSA. It includes an adventure game where you can explore endless opurtunites. Within this game you can learn how to gamble by playing the gambling game or all about stocks and crypto in our investment game!</p>
    </div>
  </a>
  <a href="{{site.baseurl}}/rpg/latest" class="toolkit-button" data-description="Learn the basics of JS and object oriented programming through hands on learning. Dive deep into the world of game coding in this underwater game where you can interact with different oceanic animals such as turtles, fishes, and more." data-authors="Author: Jane Smith">
    <img src="{{site.baseurl}}/images/toolkit-nav-buttons/rpg.png" alt="RPG Game" />
    <span class="button-name">RPG Game</span>
    <div class="description">
      <p>Learn the basics of JS and object oriented programming through hands on learning. Dive deep into the world of game coding in this underwater game where you can interact with different oceanic animals such as turtles, fishes, and more.</p>
    </div>
  </a>
  <a href="{{site.baseurl}}/navigation/game" class="toolkit-button" data-description="Explore collaboration resources that facilitate group work and team projects. Access platforms and tools designed to enhance communication, project management, and collective problem-solving." data-authors="Author: Alex Johnson">
    <img src="{{site.baseurl}}/images/toolkit-nav-buttons/platformer.png" alt="Platformer Game" />
    <span class="button-name">Platformer Game</span>
    <div class="description">
      <p>Explore collaboration resources that facilitate group work and team projects. Access platforms and tools designed to enhance communication, project management, and collective problem-solving.</p>
    </div>
  </a>
</div>

<style>
  .toolkit-buttons {
    display: flex;
    justify-content: space-around;
    align-items: flex-start;
    height: 100vh;
    margin: 0;
    padding: 20px;
  }

  .toolkit-button {
    width: 25%;
    height: auto;
    background-color: rgba(0, 0, 0, 0.5);
    color: white;x
    font-size: 1.5rem;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    transition: all 0.3s ease;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    text-align: center;
    text-decoration: none;
    padding-bottom: 20px;
  }

  .toolkit-button img {
    width: 100%;
    height: auto;
    object-fit: cover;
    border-radius: 8px;
    filter: blur(5px);
    transition: filter 0.3s ease, transform 0.3s ease;
  }

  .toolkit-button .button-name {
    position: relative;
    z-index: 1;
    font-size: 1.2rem;
    margin: 10px 0;
  }

  .toolkit-button .description {
    opacity: 0;
    position: relative;
    background: rgba(0, 0, 0, 0.8);
    color: white;
    padding: 10px;
    border-radius: 5px;
    text-align: center;
    transition: opacity 0.3s ease, transform 0.3s ease;
    white-space: normal;
    width: 100%;
    z-index: 1;
    font-size: 0.8rem;
    margin-top: 10px;
  }

  .toolkit-button:hover {
    transform: scale(1.1);
  }

  .toolkit-button:hover img {
    filter: blur(0);
  }

  .toolkit-button:hover .description {
    opacity: 1;
    transform: translateY(10px);
  }
</style>