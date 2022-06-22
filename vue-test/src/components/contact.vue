<template>
  <div class="container container-margin-top container-margin-side" id="contact">
    <h2>Contact</h2>
    <p>We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, both look and taste. Do not hesitate to contact us.</p>
    <p><b>Catering Service, 42nd Living St, 43043 New York, NY</b></p>
    <p>You can also contact us by phone 00553123-2323 or email catering@catering.com, or you can send us a message here:</p>
    <form class="form-contact" action="/action_page.php" target="_blank">
        <input type="text" placeholder="Name" size="50" required name="name">
        <input type="number" placeholder="Number of people" required name="peopleNumber">
        <input type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00">
        <input type="text" placeholder="Message" size="150" required name="message">
        <button class="button-contact" type="submit">SEND MESSAGE</button>
    </form>
  </div>
</template>

<style>

    .form-contact {
        width: 100%;
        margin-left: 2%;
    }
    .form-contact > input, .form-contact > button {
        display: block;
        font-family: "Playfair Display";
        font-size: 1.5vw;
        letter-spacing: 4px;
        color: #000000;
        outline: 0;
        border-width: 0 0 1px;
        border-color: #8c8c8c;
        padding-top: 1%;
        padding-bottom: 1%;
        margin-top: 1%;
        margin-bottom: 1%;
        width: 30%;
        min-width: 170px;
    }
    .form-contact > button{
        border: none;
        color: #000000;
    }
    .form-contact > button:hover {
        background-color: #8c8c8c;
        color: #FFFF;
        transition: 0.5s;
    }

</style>