<template>
    <div class="content">
        <div class="centered">

            <h1 class="contact-me">Contact me!</h1>
            <p class="contactdesc">Whether you're looking to collaborate on an upcoming broadcast or corporate production, have a technical question, or just want to connect, my inbox is always open.
                
                Drop a line for future projects, inquiries, or discussions, and let's build something great together.</p>
            <a class="sendmail" href="mailto:zack@zachary-richter.com?subject=Website%20Inquiry">Send Email</a>
        </div>


    </div>
</template>

<style>
.contact-me{
    font-size: 4rem;
    margin: 0rem;
}


.centered{
    display: flex;
    align-items: center;
    align-content: center;
    flex-direction: column;
    justify-content: center;
    max-width: 50rem;

}

.content{
    display: flex;
    align-items: center;
    align-content: center;
    flex-direction: column;
    justify-content: center;

}

.sendmail {
  background: #a52a2a;
  border: 1px solid #a52a2a;
  border-radius: 6px;
  box-shadow: rgba(0, 0, 0, 0.1) 1px 2px 4px;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  display: inline-block;
  font-family: nunito,roboto,proxima-nova,"proxima nova",sans-serif;
  font-size: 1.5rem;
  font-weight: 800;
  line-height: 16px;
  min-height: 40px;
  outline: 0;
  padding: 1.2rem 3.4rem;
  text-align: center;
  text-rendering: geometricprecision;
  text-transform: none;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
}

.sendmail:hover,
.sendmail:active {
  background-color: initial;
  background-position: 0 0;
  color: #a52a2a;
}

.sendmail:active {
  opacity: .5;
}

.contactdesc{
    font-size: 2rem;
    margin: 0px;
    padding-top: 2rem;
    padding-bottom: 2rem;

}
</style>