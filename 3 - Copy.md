<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
  <style>
    body {
      padding-top: 70px; /* Adjusted for fixed navbar */
    }

.vertical-line {
      border-left: 2px solid white; /* Adjust thickness and color as needed */
      height: 50px; /* Adjust height as needed */
      margin: 0 10px; /* Optional: Adjust margin for spacing */
    }


@media (max-width: 600px) {
      .vertical-line {
        border-left: none; /* Remove the border for small screens */
        border-top: 2px solid #000; /* Add a top border to create a horizontal line */
        width: 100%; /* Make it span the full width of the container */
        height: auto; /* Adjust height as needed for the horizontal line */
        margin: 10px 0; /* Optional: Adjust margin for spacing */
      }

    .navbar {
      transition: all 0.3s ease;
    }

    .navbar:hover {
      background-color: #333; /* Change background color on hover */
    }

    .navbar-brand,
    .navbar-nav .nav-link {
      color: #fff; /* Text color */
    }

    .navbar-toggler-icon {
      background-color: #fff; /* Hamburger icon color */
    }

    .navbar-nav .user-icon {
      margin-right: 10px; /* Adjust as needed */
    }

    
  </style>
  <title>Interactive Header</title>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Your Logo</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarResponsive">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#"><i class="fas fa-print"></i> Print Statement</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="fas fa-upload"></i> Load</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="fas fa-history"></i> History</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="fas fa-user-cog"></i> Admin</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="fas fa-shield-alt"></i> Security Admin</a>
        </li>

        <li class="nav-item ml-2">
          <a class="nav-link dropdown-toggle user-icon" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <i class="fas fa-user"></i>
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#"><i class="fas fa-user"></i> User Name</a>
            <a class="dropdown-item" href="#"><i class="fas fa-question-circle"></i> Help</a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</nav>

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>

</body>
</html>
