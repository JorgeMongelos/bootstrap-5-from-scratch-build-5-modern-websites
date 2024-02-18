# Section 3: Bootstrap Fundamentals Part 2.
## Bootstrap Grid & Columns.
![Bootstrap Grid](./images/8-bootstrap-grid.png)
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Bootstrap Grid Columns</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Bootstrap Grid Columns</h1>

      <!-- Basic Grid Layout -->
      <div class="row"> <!-- class="row"-->

        <div class="col bg-light border">1 of 2</div><!-- class="col bg-light border"-->
        <div class="col bg-light border">2 of 2</div><!-- class="col bg-light border"-->
      
      </div>
      <div class="row"> <!-- class="row"-->

        <div class="col bg-light border">1 of 3</div><!-- class="col bg-light border"-->
        <div class="col bg-light border">2 of 3</div><!-- class="col bg-light border"-->
        <div class="col bg-light border">3 of 3</div><!-- class="col bg-light border"-->
      
      </div>
      <br /><br />

      <!-- Column Sizes -->
      <div class="container vstack gap-3 text-light">
        <div class="row bg-primary"> <!-- class="row"-->

          <div class="col-1 border">1 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">2 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">3 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">4 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">5 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">6 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">7 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">8 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">9 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">10 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">11 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-secondary"> <!-- class="row"-->
  
          <div class="col-2 border">2 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">4 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">6 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">8 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">10 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-success"> <!-- class="row"-->
  
          <div class="col-3 border">3 of 12</div><!-- class="col bg-light border"-->
          <div class="col-3 border">6 of 12</div><!-- class="col bg-light border"-->
          <div class="col-3 border">9 of 12</div><!-- class="col bg-light border"-->
          <div class="col-3 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-danger"> <!-- class="row"-->
  
          <div class="col-4 border">4 of 12</div><!-- class="col bg-light border"-->
          <div class="col-4 border">8 of 12</div><!-- class="col bg-light border"-->
          <div class="col-4 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-warning"> <!-- class="row"-->
  
          <div class="col-5 border">5 of 12</div><!-- class="col bg-light border"-->
          <div class="col-5 border">10 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">2 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-info"> <!-- class="row"-->
  
          <div class="col-6 border">6 of 12</div><!-- class="col bg-light border"-->
          <div class="col-6 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-primary"> <!-- class="row"-->
  
          <div class="col-7 border">7 of 12</div><!-- class="col bg-light border"-->
          <div class="col-5 border">5 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-secondary"> <!-- class="row"-->
  
          <div class="col-8 border">8 of 12</div><!-- class="col bg-light border"-->
          <div class="col-4 border">4 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-success"> <!-- class="row"-->
  
          <div class="col-9 border">9 of 12</div><!-- class="col bg-light border"-->
          <div class="col-3 border">3 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-danger"> <!-- class="row"-->
  
          <div class="col-10 border">10 of 12</div><!-- class="col bg-light border"-->
          <div class="col-2 border">2 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-info"> <!-- class="row"-->
  
          <div class="col-11 border">11 of 12</div><!-- class="col bg-light border"-->
          <div class="col-1 border">1 of 12</div><!-- class="col bg-light border"-->
        
        </div>
        <div class="row bg-primary"> <!-- class="row"-->
  
          <div class="col-12 border">12 of 12</div><!-- class="col bg-light border"-->
        
        </div>
      </div>
      
      <br /><br />

      <!-- Responsive Grid -->
      <div class="row bg-info"> <!-- class="row"-->
  
        <div class="col-md-6 border">6 of 12</div> <!-- class="col-md-6 border" -->
        <div class="col-md-6 border">12 of 12</div><!-- class="col-md-6 border"-->
      
      </div>
      <div class="row bg-info"> <!-- class="row"-->
  
        <div class="col-sm-6 col-lg-4 bg-light border">6 of 12</div><!-- class="col-sm-6 col-lg-4 bg-light border""-->
        <div class="col-sm-6 col-lg-4 bg-light border">6 of 12</div><!-- class="col-sm-6 col-lg-4 bg-light border""-->
        <div class="col-sm-6 col-lg-4 bg-light border">6 of 12</div><!-- class="col-sm-6 col-lg-4 bg-light border""-->
        <div class="col-sm-6 col-lg-4 bg-light border">12 of 12</div><!--class="col-sm-6 col-lg-4 bg-light border""-->
      
      </div>
      <br /><br />

      <!-- Row Cols -->
      <div class="row row-cols-3"><!-- class="row row-cols-3" -->
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
      </div>
      <div class="row row-cols-1 row-cols-md-2 row cols-lg-3"><!-- class="row row-cols-1 row-cols-md-2 row cols-lg-3" -->
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
        <div class="col bg-light border">Column</div>
      </div>
      <br/><br/>

      <!-- Nesting -->
      <div class="row">
        <div class="col bg-light border pb-3">Column</div>
        <div class="col bg-light border pb-3">Column</div>
        <div class="col bg-light border pb-3"><!-- Nesting -->
          <div class="row">
            <div class="col text-bg-dark">Nest</div>  
            <div class="col text-bg-dark">Nest</div>   
          </div> 
        </div>
      </div>

      <br /><br />

      <!-- Gutters -->
      <div class="row g-0"><!-- class="row g-0/1/2/3/4/5" -->
        <div class="col-md-4">
          <div class="p-3 text-bg-primary">
            Content Item
          </div>
        </div>
        <div class="col-md-4">
          <div class="p-3 text-bg-primary">
            Content Item
          </div>
        </div>
        <div class="col-md-4">
          <div class="p-3 text-bg-primary">
            Content Item
          </div>
        </div>
      </div>

      <br /><br />

      <!-- Offsetting Columns -->
      <div class="row ">
        <div class="col-md-4 offset-4"><!-- class="row offset-4" -->
          <div class="p-3 text-bg-primary">
            Content Item
          </div>
        </div>
        <div class="col-md-4">
          <div class="p-3 text-bg-primary">
            Content Item
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 offset-3 border"><!-- class="col-md-6 offset-3"-->
      Hello World  
        </div>
      </div>
      <br /><br />

      <!-- Ordering -->
      <div class="row">
        <div class="col bg-light border order-4">Column 1</div><!-- class="order-4" -->
        <div class="col bg-light border order-3">Column 2</div><!-- class="order-3" -->
        <div class="col bg-light border order-2">Column 3</div><!-- class="order-2" -->
        <div class="col bg-light border order-1">Column 4</div><!-- class="order-1" -->
      </div>
      <!-- Don't go past here -->
    </div>>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Flexbox Classes
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Flexbox</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Flexbox</h1>

      <!-- Basic Flexbox -->
      <div class="d-flex"><!-- class="d-flex" -->
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Flex Column -->
      <div class="d-flex flex-column"><!-- class="d-flex flex-column" -->
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Using Screen Sizes -->
      <div class="d-flex flex-column flex-md-row"><!-- class="d-flex flex-column flex-md-row" -->
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Flex Wrap -->
      <div class="d-flex flex-wrap"><!-- class="d-flex flex-wrap" -->
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
        <div class="text-bg-success p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Justify Content -->
      <div class="d-flex justify-content-end"><!-- class="d-flex justify-content-end" -->
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
      </div>

      <br /><br />

      <div class="d-flex justify-content-around"><!-- class="d-flex justify-content-around" -->
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
      </div>

      <br /><br />

      <div class="d-flex justify-content-between"><!-- class="d-flex justify-content-between" -->
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Align Items class="" -->
      <div class="d-flex flex-column align-items-end" style="height: 300px"><!-- class="d-flex flex-column align-items-end" -->
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
        <div class="text-bg-light p-3">Flex Item</div>
      </div>

      <div class="d-flex flex-column align-items-center" style="height: 300px"><!-- class="d-flex flex-column align-items-center" -->
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
        <div class="text-bg-primary p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Align Self -->
      <div class="d-flex flex-column" style="height: 300px">
        <div class="text-bg-primary p-3 align-self-center" >Flex Item</div><!-- class=" align-self-center" -->
        <div class="text-bg-primary p-3 align-self-end">Flex Item</div><!-- class=" align-self-end" -->
        <div class="text-bg-primary p-3">Flex Item</div>
      </div>

      <br /><br />

      <!-- Flex Grow -->
      <div class="d-flex">
        <div class="text-bg-primary p-3 flex-grow-1">Flex Item</div><!-- class="flex-grow-1" -->
        <div class="text-bg-dark p-3">Flex Item</div>
        <div class="text-bg-dark p-3">Flex Item</div>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Cards
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Cards</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Cards</h1>

      <!-- Basic Text Card -->
      <div class="card" style="width: 25rem">
        <div class="card-body">
          <h5 class="card-title">Card Title</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Repudiandae, molestias dolor minus architecto vel nemo laboriosam
            aut temporibus ratione optio.
          </p>
        </div>
      </div>

      <br /><br />

      <!-- Card With Image -->
      <div class="card" style="width: 25rem">
        <img src="https://picsum.photos/200" class="card-img-top" alt="" />
        <div class="card-body">
          <h5 class="card-title">Card Title</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Repudiandae, molestias dolor minus architecto vel nemo laboriosam
            aut temporibus ratione optio.
          </p>
        </div>
      </div>

      <br /><br />

      <!-- Header & Footer -->
      <div class="card" style="width: 25rem">
        <div class="card-header">Card Header</div>
        <div class="card-body">
          <h5 class="card-title">Card Title</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Repudiandae, molestias dolor minus architecto vel nemo laboriosam
            aut temporibus ratione optio.
          </p>
        </div>
        <div class="card-footer">Card Footer</div>
      </div>

      <br /><br />

      <!-- Grid Columns & Colors -->
      <div class="row">
        <div class="col-md-3">
          <div class="card text-bg-primary">
            <div class="card-body">
              <h5 class="card-title">Card Title</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Repudiandae, molestias dolor minus architecto vel nemo
                laboriosam aut temporibus ratione optio.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card text-bg-danger">
            <div class="card-body">
              <h5 class="card-title">Card Title</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Repudiandae, molestias dolor minus architecto vel nemo
                laboriosam aut temporibus ratione optio.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card text-bg-dark">
            <div class="card-body">
              <h5 class="card-title">Card Title</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Repudiandae, molestias dolor minus architecto vel nemo
                laboriosam aut temporibus ratione optio.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card text-bg-warning">
            <div class="card-body">
              <h5 class="card-title">Card Title</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Repudiandae, molestias dolor minus architecto vel nemo
                laboriosam aut temporibus ratione optio.
              </p>
            </div>
          </div>
        </div>
      </div>

      <br /><br />

      <!-- Card Group -->
      <div class="card-group">
        <div class="card" style="width: 25rem">
          <img src="https://picsum.photos/200" class="card-img-top" alt="" />
          <div class="card-body">
            <h5 class="card-title">Card Title</h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Repudiandae, molestias dolor minus architecto vel nemo laboriosam
              aut temporibus ratione optio.
            </p>
          </div>
        </div>
        <div class="card" style="width: 25rem">
          <img src="https://picsum.photos/200" class="card-img-top" alt="" />
          <div class="card-body">
            <h5 class="card-title">Card Title</h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Repudiandae, molestias dolor minus architecto vel nemo laboriosam
              aut temporibus ratione optio.
            </p>
          </div>
        </div>
        <div class="card" style="width: 25rem">
          <img src="https://picsum.photos/200" class="card-img-top" alt="" />
          <div class="card-body">
            <h5 class="card-title">Card Title</h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Repudiandae, molestias dolor minus architecto vel nemo laboriosam
              aut temporibus ratione optio.
            </p>
          </div>
        </div>
      </div>

      <br /><br />

      <!-- Placeholders -->
      <div class="card" style="width: 18rem">
        <div class="card-body">
          <h5 class="card-title placeholder-glow">
            <span class="placeholder col-6"></span>
          </h5>
          <p class="card-text placeholder-glow">
            <span class="placeholder col-7"></span>
            <span class="placeholder col-4"></span>
            <span class="placeholder col-4"></span>
            <span class="placeholder col-6"></span>
            <span class="placeholder col-8"></span>
          </p>
          <a href="" class="btn btn-primary disabled placeholder col-6"></a>
        </div>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## List group and badges.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | List Groups & Badges</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">List Groups & Badges</h1>

      <!-- Simple List Group -->
      <ul class="list-group">
        <li class="list-group-item">Tony Stark</li>
        <li class="list-group-item">Steve Rogers</li>
        <li class="list-group-item active">Bruce Banner</li>
        <li class="list-group-item">Thor Odinson</li>
        <li class="list-group-item disabled">Rick Jones</li>
      </ul>

      <br /><br />

      <!-- Links -->
      <div class="list-group">
        <a class="list-group-item" href="#">Tony Stark</a>
        <a class="list-group-item" href="#">Steve Rogers</a>
        <a class="list-group-item active" href="#">Bruce Banner</a>
        <a class="list-group-item" href="#">Thor Odinson</a>
        <a class="list-group-item disabled" href="#">Rick Jones</a>
      </div>

      <br /><br />

      <!-- Flush Style -->
      <ul class="list-group list-group-flush">
        <li class="list-group-item">Tony Stark</li>
        <li class="list-group-item">Steve Rogers</li>
        <li class="list-group-item active">Bruce Banner</li>
        <li class="list-group-item">Thor Odinson</li>
        <li class="list-group-item disabled">Rick Jones</li>
      </ul>

      <br /><br />

      <!-- Numbered List -->
      <ol class="list-group list-group-numbered">
        <li class="list-group-item">Tony Stark</li>
        <li class="list-group-item">Steve Rogers</li>
        <li class="list-group-item active">Bruce Banner</li>
        <li class="list-group-item">Thor Odinson</li>
        <li class="list-group-item disabled">Rick Jones</li>
      </ol>

      <br /><br />

      <!-- Badges -->
      <h1>Example heading <span class="badge bg-primary">New</span></h1>
      <h2>Example heading <span class="badge bg-secondary">New</span></h2>
      <h3>Example heading <span class="badge bg-success">New</span></h3>
      <h4>Example heading <span class="badge bg-danger">New</span></h4>
      <h5>Example heading <span class="badge bg-warning">New</span></h5>
      <h6>Example heading <span class="badge bg-info">New</span></h6>

      <br /><br />

      <!-- In Button -->
      <button type="button" class="btn btn-primary">
        Notifications <span class="badge text-bg-dark">New</span>
      </button>

      <br /><br />

      <!-- Badges in List Group -->
      <ul class="list-group">
        <li
          class="list-group-item d-flex justify-content-between align-items-start"
        >
          <div class="ms-2 me-auto">
            <div class="fw-bold">Electronics</div>
            Content for this item
          </div>
          <span class="badge bg-primary rounded-pill">20</span>
        </li>
        <li
          class="list-group-item d-flex justify-content-between align-items-start"
        >
          <div class="ms-2 me-auto">
            <div class="fw-bold">Fashion</div>
            Content for this item
          </div>
          <span class="badge bg-danger rounded-pill">10</span>
        </li>
        <li
          class="list-group-item d-flex justify-content-between align-items-start"
        >
          <div class="ms-2 me-auto">
            <div class="fw-bold">Sports</div>
            Content for this item
          </div>
          <span class="badge bg-success rounded-pill">30</span>
        </li>
      </ul>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Forms & Input.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Forms & Input</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Forms & Input</h1>

      <!-- Basic Form -->
      <form>
        <div class="mb-3">
          <label for="email" class="form-label">Email Address</label>
          <input type="email" class="form-control" />
        </div>
        <div class="mb-3">
          <label for="password" class="form-label">Password</label>
          <input type="password" class="form-control" />
        </div>
        <div class="mb-3">
          <input type="checkbox" class="form-check-input" id="remember" />
          <label for="remember" class="form-check-label">Remember Me</label>
        </div>
        <input type="submit" value="Login" class="btn btn-primary" />
      </form>

      <br /><br />

      <!-- Other Fields -->
      <form>
        <!-- Select Fields -->
        <div class="mb-3">
          <select class="form-select">
            <option>Best time to call</option>
            <option value="morning">Morning</option>
            <option value="afternoon">Afternoon</option>
            <option value="evening">Evening</option>
          </select>
        </div>

        <!-- Textarea -->
        <div class="mb-3">
          <textarea class="form-control" placeholder="Message"></textarea>
        </div>

        <!-- Switch -->
        <div class="form-check form-switch">
          <input type="checkbox" class="form-check-input" />
        </div>

        <!-- Inline Checkboxes -->
        <div class="mb-3">
          <div class="form-check form-check-inline">
            <input
              type="checkbox"
              class="form-check-input"
              id="ch1"
              value="option1"
            />
            <label for="ch1" class="form-check-label">1</label>
          </div>
          <div class="form-check form-check-inline">
            <input
              type="checkbox"
              class="form-check-input"
              id="ch2"
              value="option2"
            />
            <label for="ch2" class="form-check-label">2</label>
          </div>
          <div class="form-check form-check-inline">
            <input
              type="checkbox"
              class="form-check-input"
              id="ch3"
              value="option3"
            />
            <label for="ch3" class="form-check-label">3</label>
          </div>
        </div>

        <!-- Toggle Button -->
        <div class="mb-3">
          <input type="checkbox" class="btn-check" id="btn-check" />
          <label class="btn btn-danger" for="btn-check">Button Toggle</label>
        </div>

        <!-- Range -->
        <div class="mb-3">
          <label for="range" class="form-label"></label>
          <input type="range" class="form-range" id="range" />
        </div>

        <!-- Range Steps -->
        <div class="mb-3">
          <label for="range" class="form-label"></label>
          <input
            type="range"
            class="form-range"
            id="range"
            min="0"
            max="5"
            step="0.5"
          />
        </div>
      </form>

      <!-- Input Groups -->
      <form>
        <div class="input-group mb-3">
          <span class="input-group-text">@</span>
          <input type="email" class="form-control" placeholder="Email" />
        </div>
      </form>

      <br /><br />

      <form>
        <div class="input-group">
          <input type="text" class="form-control" />
          <button class="btn btn-outline-secondary">Submit</button>
        </div>
      </form>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```
## Form Validation & Display.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Form Validation</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Form Validation Display</h1>

      <form class="needs-validation" novalidate>
        <div class="mb-3">
          <label for="username" class="form-label">Username</label>
          <input type="text" class="form-control" id="username" required />
          <div class="valid-feedback">Looks Good</div>
          <div class="invalid-feedback">Please pick a username</div>
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email address</label>
          <input type="email" class="form-control" id="email" required />
          <div class="valid-feedback">Looks Good</div>
          <div class="invalid-feedback">Please pick a valid email</div>
        </div>
        <div class="mb-3">
          <label for="city" class="form-label">City</label>
          <input type="text" class="form-control" id="city" required />
          <div class="valid-feedback">Looks Good</div>
          <div class="invalid-feedback">Please pick a city</div>
        </div>

        <div class="mb-3">
          <div class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="invalidCheck"
              required
            />
            <label class="form-check-label" for="invalidCheck">
              Agree to terms and conditions
            </label>
            <div class="invalid-feedback">You must agree to the terms</div>
          </div>
        </div>

        <input type="submit" class="btn btn-primary" value="Submit" />
      </form>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
    <script>
      const form = document.querySelector('.needs-validation');

      form.addEventListener('submit', (e) => {
        if (!form.checkValidity()) {
          e.preventDefault();
        } else {
          alert('success');
        }

        form.classList.add('was-validated');
      });
    </script>
  </body>
</html>
```
## Alerts & Progress Bars.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Alerts & Progress Bars</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Alerts & Progress Bars</h1>

      <!-- Alerts -->
      <div class="alert alert-primary" role="alert">
        This is a primary alert!
      </div>
      <div class="alert alert-secondary" role="alert">
        This is a secondary alert!
      </div>
      <div class="alert alert-success" role="alert">
        This is a success alert!
      </div>
      <div class="alert alert-danger" role="alert">This is a danger alert!</div>
      <div class="alert alert-warning" role="alert">
        This is a warning alert!
      </div>
      <div class="alert alert-info" role="alert">This is a info alert!</div>
      <div class="alert alert-light" role="alert">This is a light alert!</div>
      <div class="alert alert-dark" role="alert">This is a dark alert!</div>

      <br /><br />

      <!-- Alert with link -->

      <div class="alert alert-danger" role="alert">
        This is a primary alert! <a href="#" class="alert-link">Example link</a>
      </div>

      <br /><br />

      <!-- Additional Content -->
      <div class="alert alert-success" role="alert">
        <h4 class="alert-heading">Well Done</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet,
          beatae.
        </p>
        <hr />
        <p>Lorem ipsum dolor sit amet.</p>
      </div>

      <br /><br />

      <!-- Dismissing -->
      <div class="alert alert-danger alert-dismissible fade show" role="alert">
        <button class="btn-close" data-bs-dismiss="alert"></button>
        Something went wrong
      </div>

      <br /><br />

      <!-- Progress Bars -->
      <div
        class="progress mb-4"
        role="progressbar"
        aria-valuenow="25"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        <div class="progress-bar" style="width: 25%"></div>
      </div>

      <div
        class="progress mb-4"
        role="progressbar"
        aria-valuenow="50"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        <div class="progress-bar bg-success" style="width: 50%"></div>
      </div>

      <br /><br />

      <!-- Labels -->
      <div
        class="progress mb-4"
        role="progressbar"
        aria-valuenow="40"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        <div class="progress-bar bg-danger" style="width: 40%">40%</div>
      </div>

      <br /><br />

      <!-- Stripes -->
      <div
        class="progress mb-4"
        role="progressbar"
        aria-valuenow="50"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        <div
          class="progress-bar progress-bar-striped bg-success"
          style="width: 50%"
        ></div>
      </div>

      <br /><br />

      <!-- Animated Stripes -->
      <div
        class="progress mb-4"
        role="progressbar"
        aria-valuenow="50"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        <div
          class="progress-bar progress-bar-striped progress-bar-animated bg-warning"
          style="width: 50%"
        ></div>
      </div>

      <br /><br />

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```
## Tables
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Tables</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Tables</h1>
      <!-- Basic Tables -->
      <table class="table">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>1</th>
            <td>Tony Stark</td>
            <td>ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>

      <br /><br />

      <!-- Variants -->
      <table class="table table-dark">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr class="table-danger">
            <th>1</th>
            <td>Tony Stark</td>
            <td class="table-warning">ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>
      <br /><br />

      <!-- Striped -->
      <table class="table table-striped">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>1</th>
            <td>Tony Stark</td>
            <td>ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>

      <br /><br />

      <!-- Hoverable Rows -->
      <table class="table table-hover">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>1</th>
            <td>Tony Stark</td>
            <td>ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>

      <br /><br />

      <!-- Bordered Tables -->
      <table class="table table-bordered">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>1</th>
            <td>Tony Stark</td>
            <td>ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>

      <br /><br />

      <!-- Borderless Tables -->
      <table class="table table-borderless">
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Email</th>
            <th>Position</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>1</th>
            <td>Tony Stark</td>
            <td>ironman@gmail.com</td>
            <td>Senior Web Developer</td>
          </tr>
          <tr>
            <th>2</th>
            <td>Steve Rogers</td>
            <td>captain@gmail.com</td>
            <td>UI Designer</td>
          </tr>
          <tr>
            <th>3</th>
            <td>Bruce Banner</td>
            <td>hulk@gmail.com</td>
            <td>Junior Web Developer</td>
          </tr>
        </tbody>
      </table>
      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```
## Breadcrumb & Pagination.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Breadcrumb & Pagination</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Breadcrumb & Pagination</h1>

      <!-- Breadcrumb -->
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item"><a href="#">Home</a></li>
          <li class="breadcrumb-item"><a href="#">About</a></li>
          <li class="breadcrumb-item active" aria-current="page">
            <a href="#">Staff</a>
          </li>
        </ol>
      </nav>

      <br /><br />

      <!-- Dividers -->
      <nav style="--bs-breadcrumb-divider: '>'" aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item"><a href="#">Home</a></li>
          <li class="breadcrumb-item"><a href="#">About</a></li>
          <li class="breadcrumb-item active" aria-current="page">
            <a href="#">Staff</a>
          </li>
        </ol>
      </nav>

      <br /><br />

      <!-- Pagination -->
      <nav aria-label="page navigation">
        <ul class="pagination">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <br /><br />

      <!-- Active & Disabled States -->
      <nav aria-label="page navigation">
        <ul class="pagination">
          <li class="page-item disabled">
            <a href="#" class="page-link">Previous</a>
          </li>
          <li class="page-item active"><a href="#" class="page-link">1</a></li>
          <li class="page-item"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <br /><br />

      <!-- Sizing -->
      <nav aria-label="page navigation">
        <ul class="pagination pagination-sm">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item active"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <nav aria-label="page navigation">
        <ul class="pagination pagination-lg">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item active"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <br /><br />

      <!-- Alignment -->
      <nav aria-label="page navigation">
        <ul class="pagination justify-content-end">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item active"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <nav aria-label="page navigation">
        <ul class="pagination justify-content-center">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item active"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item">
            <a href="#" class="page-link" aria-label="Next">&raquo;</a>
          </li>
        </ul>
      </nav>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Other CSS Utilities.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Other CSS Utilities</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Other CSS Utilities</h1>

      <!-- Truncate Text -->
      <div class="row">
        <div class="col-4 text-truncate">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt,
          nisi blanditiis. Voluptatibus libero deleniti delectus fugiat pariatur
          cum aliquam maxime.
        </div>
      </div>

      <br /><br />

      <!-- Stretched Link -->
      <div class="card" style="width: 18rem">
        <img src="https://picsum.photos/200" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card with stretched link</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Recusandae, assumenda!
          </p>
          <a href="#" class="btn btn-primary stretched-link">Go somewhere</a>
        </div>
      </div>

      <br /><br />

      <!-- Invisible & Visible -->
      <div class="visible">...</div>
      <div class="invisible">...</div>
      <div class="visible">...</div>

      <br /><br />

      <!-- Floats -->
      <div class="float-start">Float start</div>
      <br />
      <div class="float-end">Float end</div>
      <br />
      <div class="float-none">Don't float</div>
      <br />
      <!-- Responsive Float -->
      <div class="float-lg-end">Float on large screens</div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
