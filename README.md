<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Advaitha Kitchen</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Google Font: Rubik Distressed -->
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Distressed&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
    }
    .navbar {
      margin-bottom: 20px;
    }
    
    .navbar-brand {
      font-family: 'Rubik Distressed', cursive;
      font-size: 2rem; 
    }
    .carousel-item img {
     width: 100%;
     height: auto;   
    }
    footer {
      background-color: #343a40;
      color: #fff;
      padding: 20px 0;
      margin-top: 30px;
      text-align: center;
      border-radius: 8px;
    }
    .breadcrumb {
      background: #e9ecef;
      padding: 10px;
      border-radius: 8px;
    }
    .btn-group .btn {
      border-radius: 20px;
    }
    .badge {
      font-size: 14px;
    }
    .section {
      padding: 40px 0;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Advaitha Kitchen</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#menu">Menu</a></li>
          <li class="nav-item"><a class="nav-link" href="#specials">Specials</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Alert -->
  <div id="home" class="container">
    <div class="alert alert-warning text-center" role="alert">
      🍽️ Welcome to <strong>Advaitha Kitchen</strong> — Serving Freshness & Flavor Every Day!
    </div>
  </div>

  <!-- Carousel -->
  <div id="foodCarousel" class="carousel slide container" data-bs-ride="carousel">
    <div class="carousel-inner rounded">
      <div class="carousel-item active">
        <img src="pic.jpeg" class="d-block w-100" alt="Veg Food">
      </div>
      <div class="carousel-item">
        <img src="pic1.jpeg" class="d-block w-100" alt="Vegetarian Dishes">
      </div>
      <div class="carousel-item">
        <img src="pic2.jpeg" class="d-block w-100" alt="Veg Thali">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#foodCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#foodCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>

  <!-- Breadcrumb -->
  <nav class="container mt-4" aria-label="breadcrumb">
    <ol class="breadcrumb">
      <li class="breadcrumb-item"><a href="#home">Home</a></li>
      <li class="breadcrumb-item"><a href="#menu">Menu</a></li>
      <li class="breadcrumb-item active" aria-current="page">Today's Specials</li>
    </ol>
  </nav>

  <!-- Buttons & Button Group -->
  <div class="container text-center my-4">
    <div class="btn-group">
      <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#orderNowModal">Order Now</button>
      <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#bookTableModal">Book a Table</button>
      <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#offersModal">Today's Offer</button>
    </div>
  </div>

  <!-- Menu Section -->
  <div id="menu" class="container section text-center">
    <h2>Our Veg Menu</h2>
    <span class="badge bg-primary">South Indian</span>
    <span class="badge bg-success">North Indian</span>
    <span class="badge bg-warning text-dark">Desserts</span>
    <div class="row mt-4">
      <div class="col-md-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">South Indian Delights</h5>
            <p class="card-text">Idli, Dosa, Vada, Upma, Pongal</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card"> 
        <div class="card-body">
            <h5 class="card-title">North Indian Tastes</h5>
            <p class="card-text">Paneer Butter Masala, Dal Tadka, Roti, Biryani</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Sweet Desserts</h5>
            <p class="card-text">Gulab Jamun, Rasmalai, Kheer, Jalebi</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Specials Section -->
  <div id="specials" class="container section text-center bg-light">
    <h2>Today's Specials</h2>
    <p class="lead">Chef’s Choice for the Day</p>
    <ul class="list-group">
      <li class="list-group-item">🌱 Veg Biryani with Raita</li>
      <li class="list-group-item">🥗 Paneer Tikka Masala</li>
      <li class="list-group-item">🍛 Vegetable Kurma with Parotta</li>
    </ul>
  </div>

  <!-- Contact Section -->
  <div id="contact" class="container section">
    <h2 class="text-center">Contact Us</h2>
    <p class="text-center">📍 Hyderabad, India | ☎️ +91 9876543210 | ✉️ info@advaithakitchen.com</p>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Advaitha Kitchen | Taste the Tradition, Love the Flavor ❤️</p>
  </footer>

  <!-- Order Now Modal -->
<div class="modal fade" id="orderNowModal" tabindex="-1">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Veg Menu - Order Now</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body row">
        
        <!-- Menu -->
        <div class="col-md-6">
          <button class="btn btn-outline-primary w-100 mb-2" onclick="addToCart('Idli',50)">Idli - ₹50</button>
          <button class="btn btn-outline-primary w-100 mb-2" onclick="addToCart('Dosa',60)">Dosa - ₹60</button>
          <button class="btn btn-outline-primary w-100 mb-2" onclick="addToCart('Paneer Curry',120)">Paneer Curry - ₹120</button>
          <button class="btn btn-outline-primary w-100 mb-2" onclick="addToCart('Veg Biryani',150)">Veg Biryani - ₹150</button>
        </div>

        <!-- Cart -->
        <div class="col-md-6">
          <h6>🛒 Cart</h6>
          <ul id="cartList" class="list-group mb-2"></ul>
          <p>Total: ₹<span id="cartTotal">0</span></p>
          <button id="payBtn" class="btn btn-success w-100" style="display:none;">Pay Now</button>

          <!-- Payment Options (hidden initially) -->
          <div id="paymentOptions" style="display:none;" class="mt-3">
            <h6>Select Payment Method</h6>
            <select id="paymentMethod" class="form-select mb-2">
              <option value="UPI">UPI</option>
              <option value="Card">Card</option>
              <option value="Cash">Cash on Delivery</option>
            </select>
            <button class="btn btn-primary w-100" onclick="confirmPayment()">Confirm Payment</button>
          </div>

          <!-- Success Message -->
          <div id="payMsg" class="alert alert-success mt-3" style="display:none;">✅ Payment Successful!</div>
        </div>

      </div>
    </div>
  </div>
</div>

<script>
  let total=0;
  function addToCart(item,price){
    total+=price;
    document.getElementById("cartList").innerHTML+=`<li class="list-group-item">${item} - ₹${price}</li>`;
    document.getElementById("cartTotal").innerText=total;
    document.getElementById("payBtn").style.display="block";
  }

  // Show payment options
  document.getElementById("payBtn").onclick=()=>{
    document.getElementById("paymentOptions").style.display="block";
  }

  // Confirm payment
  function confirmPayment(){
    let method=document.getElementById("paymentMethod").value;
    document.getElementById("payMsg").innerText="✅ Payment Successful via " + method + "!";
    document.getElementById("payMsg").style.display="block";

    // reset cart
    document.getElementById("cartList").innerHTML="";
    document.getElementById("cartTotal").innerText=0;
    document.getElementById("payBtn").style.display="none";
    document.getElementById("paymentOptions").style.display="none";
    total=0;
  }
</script>


  <!-- Offers Modal -->
  <div class="modal fade" id="offersModal" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Today's Special Offer 🎉</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
        </div>
        <div class="modal-body">
          <p>🌟 Get <strong>20% OFF</strong> on all Veg Biryani orders today!</p>
          <p>🍮 Free Gulab Jamun with every Thali.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Book Table Modal -->
<div class="modal fade" id="bookTableModal" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Book a Table</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">
        <!-- Booking Form -->
        <form id="bookingForm">
          <div class="mb-3">
            <label for="date" class="form-label">Date</label>
            <input type="date" class="form-control" id="date" required>
          </div>
          <div class="mb-3">
            <label for="time" class="form-label">Time</label>
            <input type="time" class="form-control" id="time" required>
          </div>
          <div class="mb-3">
            <label for="people" class="form-label">Number of People</label>
            <input type="number" class="form-control" id="people" min="1" max="20" required>
          </div>
          <button type="submit" class="btn btn-success w-100">Confirm Booking</button>
        </form>

        <!-- Success Message -->
        <div id="bookingSuccess" class="alert alert-success text-center mt-3" style="display: none;">
          ✅ Table successfully booked!
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script>
  // Booking Form Handling
  document.getElementById("bookingForm").addEventListener("submit", function(event){
    event.preventDefault(); 
    document.getElementById("bookingSuccess").style.display = "block"; 
  });
</script>
</body>
</html>
