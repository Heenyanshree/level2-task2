# level2-task2
Travel booking system
!DOCTYPE html>
<html>
<head>
    <title>Travel Booking System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            padding: 20px;
        }

        .search-form {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
        }

        .form-group {
            margin-bottom: 10px;
        }

        label {
            display: block;
            font-weight: bold;
        }

        input[type="text"],
        input[type="date"],
        select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        .submit-button {
            text-align: center;
            margin-top: 20px;
        }

        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Flight Booking</h1>
        <div class="search-form">
            <form>
                <div class="form-group">
                    <label for="departure">Departure:</label>
                    <input type="text" id="departure" placeholder="Departure city or airport">
                </div>
                <div class="form-group">
                    <label for="arrival">Arrival:</label>
                    <input type="text" id="arrival" placeholder="Arrival city or airport">
                </div>
                <div class="form-group">
                    <label for="departure-date">Departure Date:</label>
                    <input type="date" id="departure-date">
                </div>
                <div class="form-group">
                    <label for="passengers">Passengers:</label>
                    <select id="passengers">
                        <option value="1">1</option>
                        <option value="2">2</option>
                        <option value="3">3</option>
                        <option value="4">4</option>
                    </select>
                </div>
                <div class="submit-button">
                    <button type="submit">Search Flights</button>
                </div>
            </form>
        </div>
    </div>
</body>
</html>
