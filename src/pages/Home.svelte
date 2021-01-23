<script>
  export let data;
</script>
<body>
  <div class="body">

      <div id="header">


          <div class="tab tl" id="home">Home</div>


          <div class="btn-group-l">
              <div class="tab" id="profile" data-connect=1>
                  <p>Profile</p>
              </div>
              <div class="tab" id="about" data-connect=2>
                  <p>About</p>
              </div>
              <div class="tab" id="projects" data-connect=3>
                  <p>Projects</p>
              </div>
              <div class="tab" id="contact" data-connect=4>
                  <p>Contact</p>
              </div>
              <div class="tab" id="resources" data-connect=5>
                  <p>Resources</p>
              </div>
          </div>

          <div class="btn-group-r">
              <div class="tabr" id="log">Login/Register</div>
          </div>
      </div>


      <div class="container">
          <div class="round">

              <div class="logo-wrap">
                  <h1>FullStack_Developer</h1>
              </div>
              <div class="name-wrap">
                  <h3>Mickey</h3>
              </div>
              <div class="circ-Text" id="shadow">
              </div>

          </div>
          </div>
          </div>
          </body>
{JSON.stringify(data, null, 2)}
