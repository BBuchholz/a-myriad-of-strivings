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
  <div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3  box-shadow">
      <h1 class="my-0 mr-md-auto font-weight-normal">A Myriad Of Services</h1>
      <nav class="my-2 my-md-0 mr-md-3">
        <a class="p-2" href="#">Features</a>
        <a class="p-2" href="#">Support</a>
        <a class="p-2" href="#">Pricing</a>
      </nav>
      <a href={contact_href_consult} target="_blank" class="btn btn-outline-primary">Request A Free Consultation</a>
    </div>

    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <!-- <h1 class="display-4">Offerings</h1> -->
      <p class="lead">Here's an informal video detailing where we are and where we are going</p>

<!-- I WANNA EMBED VIDEO HERE -->
      <iframe width="270" height="480" src="https://www.youtube.com/embed/90GoiMIhSwI">
      </iframe>

    </div>

    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <h1 class="display-4">Offerings</h1>
      <p class="lead">These are the current services we are preparing to offer (click the buttons to send us an inquiry or to be notified about updates)</p>

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

          <div>
            <div>
              <div><div style="
              overflow: auto;
              display: flex;
              flex-direction: column;
              justify-content: flex-end;
              align-items: center;
              width: 259px;
              background: #FFFFFF;
              border: 1px solid rgba(0, 0, 0, 0.1);
              box-shadow: -2px 10px 5px rgba(0, 0, 0, 0);
              border-radius: 10px;
              font-family: SQ Market, SQ Market, Helvetica, Arial, sans-serif;
              ">
              <div style="padding: 20px;">
              <p style="
                font-size: 18px;
                line-height: 20px;
              ">Dues</p>
              <p style="
                font-size: 18px;
                line-height: 20px;
                font-weight: 600;
              ">$1.00</p>
              <a target="_blank" data-url="https://square.link/u/PdsQgNIA?src=embd" href="https://square.link/u/PdsQgNIA?src=embed" style="
                display: inline-block;
                font-size: 18px;
                line-height: 48px;
                height: 48px;
                color: #ffffff;
                min-width: 212px;
                background-color: #19802a;
                text-align: center;
                box-shadow: 0 0 0 1px rgba(0,0,0,.1) inset;
                border-radius: 6px;
              ">Pay now</a>
              </div>
            </div>
            </div>

              <script>
                function showCheckoutWindow(e) {
                  e.preventDefault();

                  const url = document.getElementById('embedded-checkout-modal-checkout-button').getAttribute('data-url');
                  const title = 'Square Online Checkout';

                  // Some platforms embed in an iframe, so we want to top window to calculate sizes correctly
                  const topWindow = window.top ? window.top : window;

                  // Fixes dual-screen position                                Most browsers          Firefox
                  const dualScreenLeft = topWindow.screenLeft !==  undefined ? topWindow.screenLeft : topWindow.screenX;
                  const dualScreenTop = topWindow.screenTop !==  undefined   ? topWindow.screenTop  : topWindow.screenY;

                  const width = topWindow.innerWidth ? topWindow.innerWidth : document.documentElement.clientWidth ? document.documentElement.clientWidth : screen.width;
                  const height = topWindow.innerHeight ? topWindow.innerHeight : document.documentElement.clientHeight ? document.documentElement.clientHeight : screen.height;

                  const h = height * .75;
                  const w = 500;

                  const systemZoom = width / topWindow.screen.availWidth;
                  const left = (width - w) / 2 / systemZoom + dualScreenLeft;
                  const top = (height - h) / 2 / systemZoom + dualScreenTop;
                  const newWindow = window.open(url, title, `scrollbars=yes, width=${w / systemZoom}, height=${h / systemZoom}, top=${top}, left=${left}`);

                  if (window.focus) newWindow.focus();
                }

                // This overrides the default checkout button click handler to show the embed modal
                // instead of opening a new tab with the given link url
                document.getElementById('embedded-checkout-modal-checkout-button').addEventListener('click', function (e) {
                  showCheckoutWindow(e);
                });
              </script>
            </div>
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