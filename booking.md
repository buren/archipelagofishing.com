---
layout: page
title: "Palladium Cinema"
description: "Like noting you've ever seen before."
header-img: "img/old_cinema.jpg"
---


<div class="row">
  <div class="col-md-4 col-md-offset-2">
    <h2>Choose tickets:</h2>
    <p>
      <img src="{{ site.baseurl }}/img/seating_plan.png" alt="Avaiable tickets">
    </p>
  </div>
  <div class="col-md-4">
    <p>
      <strong>Number of tickets:</strong>
      <select name="tickets" id="ticketNo">
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        <option value="6">6</option>
        <option value="7">7</option>
        <option value="8">8</option>
        <option value="9">9</option>
        <option value="10">10</option>
        <option value="11">11</option>
        <option value="12">12</option>
      </select>
    </p>
    <p>
      <strong>Total:</strong>
      <span id="dollar">$0</span>
    </p>
    <a href="#" class="btn btn-success">Checkout</a>
  </div>
</div>