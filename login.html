<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Example</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</head>
<body>
    <h1>Login Page</h1>
    
    <div class="container mt-5">
        <h1 class="mb-4">Login Page</h1>
        
        <form id="loginForm">
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" class="form-control" id="username" name="username" required>
            </div>

            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" class="form-control" id="password" name="password" required>
            </div>

            <button type="button" class="btn btn-primary" onclick="login()">Login</button>
        </form>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </div>
    </form>

    <div id="tokenDisplay"></div>
	 <script>
        async function login() {
            // Get input values
            var username = document.getElementById('username').value;
            var password = document.getElementById('password').value;

            try {
                // Gửi yêu cầu đăng nhập đến server và nhận phản hồi
                var response = await fetch('http://localhost:8080/authenticate', {
                    method: 'POST',
                    headers: {
 'Authorization': 'Bearer ' + ' ',
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify({
                        username: username,
                        password: password,
                    }),
                });
 		 var data = await response.json();
                // Kiểm tra xem yêu cầu có thành công hay không
                if (response.ok) {
                    // Chuyển đổi phản hồi sang JSON
                  
			//console.log(data.messenger)
                    // Hiển thị token và thông tin liên quan
                    displayToken(data.token, data.role);
                } else {
			console.log(data.messenger)
                }
            } catch (error) {
              
            }
        }

        // Hàm hiển thị token
        function displayToken(token, role) {
            var tokenDisplay = document.getElementById('tokenDisplay');
            tokenDisplay.innerHTML = 'Token: ' + token + '<br>Role: ' + role;
        }
    </script>
</body>
</html>
