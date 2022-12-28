<script>

let contact_href = "mailto: syndicated.circuitry@gmail.com";
let contact_href_consult = contact_href + "?subject=Request%20A%20Free%20Consultation";
let contact_href_homework = contact_href + "?subject=Homework%20Help%20And%20Tutoring";
let contact_href_devwork = contact_href + "?subject=Dev%20Work";
let contact_href_greatwork = contact_href + "?subject=Apprenticeships";

function alertTodo(anchorComponent){

  // TODO: implement everywhere this is called
  alert(anchorComponent + " under construction, check back later");
}

</script>

<div class="main">
  <div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3  border-bottom box-shadow">
      <h1 class="my-0 mr-md-auto font-weight-normal">A Myriad Of Services</h1>
      <nav class="my-2 my-md-0 mr-md-3">
        <a class="p-2" href="#">Features</a>
        <a class="p-2" href="#">Support</a>
        <a class="p-2" href="#">Pricing</a>
      </nav>
      <a href={contact_href_consult} target="_blank" class="btn btn-outline-primary">Request A Free Consultation</a>
    </div>

    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <h1 class="display-4">Offerings</h1>
      <p class="lead">This is where we will be displaying the services we can offer, and these offerings will expand as our apprentice-generalists expand their skill sets.</p>
    </div>

    <div class="container">
      <div class="card-deck mb-3 text-center">
        
        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">General Support</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$10 <small class="text-muted">/ consult</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Any General Tech Questions Or Advice Needed</li>
              <li>Homework Help and Tutoring Requests By Appointment (on call for additional fee)</li>
            </ul>
            <a href={contact_href_homework} target="_blank" class="btn btn-lg btn-block btn-primary">Homework Help Inquiries Welcome</a>
          </div>
        </div>

        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Dev Work</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$20 <small class="text-muted">/ feature</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Component Based Model</li>
              <li>Pick The Features You Want</li>
              <li>Delivery Schedules Based On Number Of Features Needed</li>
            </ul>
            <a href={contact_href_devwork} target="_blank" class="btn btn-lg btn-block btn-primary">Request More Info</a>
          </div>
        </div>
        
        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Apprenticeships</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$0 <small class="text-muted">/ mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Hands On Learning Building Products and Services With Experienced Developers</li>
              <li>Guild Based Participation Structure (Contributions Earn Membership In Tiered Progression Format)</li>
              <li>Mentoring and Support For Freelance Career Development And Trajectory</li>
            </ul>
            <a href={contact_href_greatwork} target="_blank" class="btn btn-lg btn-block btn-primary">Wanna Join The Ranks?</a>
          </div>
        </div>
      </div>

      <footer class="pt-4 my-md-5 pt-md-5 border-top">
        <div class="row">

          <!-- TODO: COPYRIGHT RESEARCH -->
          <!-- <div class="col-12 col-md">
            <img class="mb-2" src="https://getbootstrap.com/docs/4.0/assets/brand/bootstrap-solid.svg" alt="" width="24" height="24">
            <small class="d-block mb-3 text-muted">&copy; 2022</small>
          </div> -->

          <!-- TODO: expand this -->
          <!-- <div class="col-6 col-md">
            <h5>Features</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Cool stuff</a></li>
              <li><a class="text-muted" href="#">Random feature</a></li>
              <li><a class="text-muted" href="#">Team feature</a></li>
              <li><a class="text-muted" href="#">Stuff for developers</a></li>
              <li><a class="text-muted" href="#">Another one</a></li>
              <li><a class="text-muted" href="#">Last time</a></li>
            </ul>
          </div>
          <div class="col-6 col-md">
            <h5>Resources</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Resource</a></li>
              <li><a class="text-muted" href="#">Resource name</a></li>
              <li><a class="text-muted" href="#">Another resource</a></li>
              <li><a class="text-muted" href="#">Final resource</a></li>
            </ul>
          </div> -->

          <div class="col-6 col-md">
            <h5>About</h5>
            <ul class="list-unstyled text-small">
              <li><a class="text-muted" href="#">Team</a></li>
              <li><a class="text-muted" href="#">Locations</a></li>
              <li><a class="text-muted" href="#">Privacy</a></li>
              <li><a class="text-muted" href="#">Terms</a></li>
            </ul>
          </div>

          <div class="col-6 col-md">
            <h5>Contact</h5>
            <ul class="list-unstyled text-small">
              <li><a href={contact_href} target="_blank">Email Us</a>
            </ul>
          </div>
        </div>
      </footer>
    </div>
</div>


<style>

  .main {
    font-size: 14px;
  }
  @media (min-width: 768px) {
    html {
      font-size: 16px;
    }
  }

  .container {
    max-width: 960px;
  }

  .pricing-header {
    max-width: 700px;
  }

  .card-deck .card {
    min-width: 220px;
  }

  .border-top { border-top: 1px solid #e5e5e5; }
  .border-bottom { border-bottom: 1px solid #e5e5e5; }

  .box-shadow { box-shadow: 0 .25rem .75rem rgba(0, 0, 0, .05); }
  
</style>