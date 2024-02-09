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
  
        <div class="col-md-6 border">6 of 12</div><!-- class="col bg-light border"-->
        <div class="col-md-6 border">12 of 12</div><!-- class="col bg-light border"-->
      
      </div>
      <div class="row bg-info"> <!-- class="row"-->
  
        <div class="col-sm-6 border">6 of 12</div><!-- class="col bg-light border"-->
        <div class="col-sm-6 border">6 of 12</div><!-- class="col bg-light border"-->
        <div class="col-sm-6 border">6 of 12</div><!-- class="col bg-light border"-->
        <div class="col-sm-6 border">12 of 12</div><!-- class="col bg-light border"-->
      
      </div>
      <br /><br />

      <!-- Row Cols -->

      <br /><br />

      <br /><br />

      <!-- Nesting -->

      <br /><br />

      <!-- Gutters -->

      <br /><br />

      <!-- Offsetting Columns -->

      <br /><br />

      <!-- Ordering -->

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```

# Template
<table>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td></br> 
        </td>
        <td>
          <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
          </ul>
      </td>
      </tr>
    </tbody>
</table> 

```HTML

```
<table>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2/9/2024</li>
            <li>2 - 2/9/2024</li>
            <li>3 - 2/9/2024</li>
            <li>4 - 2/9/2024</li>
          </ul>
      </td>
      </tr>
    </tbody>
</table> 