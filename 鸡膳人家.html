<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>饭店点餐程序</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        h1 {
            text-align: center;
        }

        #menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .dish {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            text-align: center;
            width: 200px;
            cursor: pointer;
        }

        #cart {
            margin-top: 20px;
            border: 1px solid #ccc;
            padding: 10px;
        }

        #total {
            text-align: right;
        }

        #checkoutBtn {
            margin-top: 10px;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
        }

        #clearCartBtn {
            margin-top: 10px;
            padding: 10px;
            background-color: #f44336;
            color: white;
            cursor: pointer;
        }

        .removeItemBtn {
            color: #f44336;
            cursor: pointer;
            margin-left: 5px;
        }
    </style>
</head>
<body>

    <h1>欢迎光临鸡膳人家</h1>

    <div id="menu">
        <div class="dish" onclick="addToCart('黄芪鸡', 218)">黄芪鸡<br>￥218</div>
        <div class="dish" onclick="addToCart('辣子', 18)">辣子<br>￥18</div>
        <div class="dish" onclick="addToCart('小饼', 12)">小饼<br>￥12</div>
        <div class="dish" onclick="addToCart('牛腱子肉', 68)">牛腱子肉<br>￥68</div>
        <div class="dish" onclick="addToCart('猪肝', 48)">猪肝<br>￥48</div>
        <div class="dish" onclick="addToCart('香辣双拼', 56)">香辣双拼<br>￥56</div>
        <div class="dish" onclick="addToCart('板蓝根青菜', 26)">板蓝根青菜<br>￥26</div>
        <div class="dish" onclick="addToCart('豆腐丝', 18)">豆腐丝<br>￥18</div>
        <div class="dish" onclick="addToCart('双椒变蛋', 18)">双椒变蛋<br>￥18</div>
        <div class="dish" onclick="addToCart('土豆', 8)">土豆<br>￥8</div>
        <div class="dish" onclick="addToCart('豆腐', 8)">豆腐<br>￥8</div>
        <div class="dish" onclick="addToCart('笋片', 12)">笋片<br>￥12</div>
        <div class="dish" onclick="addToCart('原生菜', 16)">原生菜<br>￥16</div>
        <div class="dish" onclick="addToCart('虾滑', 32)">虾滑<br>￥32</div>
        <div class="dish" onclick="addToCart('纸巾', 3)">纸巾<br>￥3</div>
        <!-- 添加更多菜品 -->
    </div>

    <div id="cart">
        <h2>购物车</h2>
        <ul id="cartItems"></ul>
        <div id="total">总计：￥<span id="totalAmount">0</span></div>
        <button id="checkoutBtn" onclick="checkout()">结账</button>
        <button id="clearCartBtn" onclick="clearCart()">清空购物车</button>
    </div>

    <script>
        let cartItems = [];
        let totalAmount = 0;

        function addToCart(name, price) {
            cartItems.push({ name, price });
            totalAmount += price;
            updateCart();
        }

        function removeItem(index) {
            totalAmount -= cartItems[index].price;
            cartItems.splice(index, 1);
            updateCart();
        }

        function updateCart() {
            const cartList = document.getElementById("cartItems");
            const totalAmountElement = document.getElementById("totalAmount");

            cartList.innerHTML = "";

            cartItems.forEach((item, index) => {
                const listItem = document.createElement("li");
                listItem.textContent = `${item.name} - ￥${item.price}`;
                const removeBtn = document.createElement("span");
                removeBtn.className = "removeItemBtn";
                removeBtn.textContent = "删除";
                removeBtn.onclick = function() { removeItem(index) };
                listItem.appendChild(removeBtn);
                cartList.appendChild(listItem);
            });

            totalAmountElement.textContent = totalAmount;
        }

        function checkout() {
            alert("结账成功！总金额：￥" + totalAmount);
            // 这里可以添加更多的结账处理逻辑，比如向后端发送订单信息等
        }

        function clearCart() {
            cartItems = [];
            totalAmount = 0;
            updateCart();
        }
    </script>

</body>
</html>
