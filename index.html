<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic-Tac-Toe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .board {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-template-rows: repeat(3, 100px);
            gap: 5px;
            justify-content: center;
            margin-top: 20px;
        }
        .cell {
            width: 100px;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            background-color: #f0f0f0;
            border: 2px solid #000;
            cursor: pointer;
        }
        .cell.taken {
            cursor: not-allowed;
        }
        .message {
            margin-top: 20px;
            font-size: 1.5em;
        }
        button {
            margin-top: 20px;
            padding: 10px;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <h1>Tic-Tac-Toe</h1>
    <div class="board" id="board"></div>
    <div class="message" id="message"></div>
    <button onclick="resetGame()">Restart</button>

    <script>
        const board = document.getElementById("board");
        const message = document.getElementById("message");
        let currentPlayer = "X";
        let gameBoard = ["", "", "", "", "", "", "", "", ""];
        
        function checkWinner() {
            const winPatterns = [
                [0, 1, 2], [3, 4, 5], [6, 7, 8], 
                [0, 3, 6], [1, 4, 7], [2, 5, 8], 
                [0, 4, 8], [2, 4, 6]
            ];
            
            for (const pattern of winPatterns) {
                const [a, b, c] = pattern;
                if (gameBoard[a] && gameBoard[a] === gameBoard[b] && gameBoard[a] === gameBoard[c]) {
                    message.innerText = `${gameBoard[a]} Wins!`;
                    return true;
                }
            }
            if (!gameBoard.includes("")) {
                message.innerText = "It's a Draw!";
                return true;
            }
            return false;
        }
        
        function makeMove(index) {
            if (!gameBoard[index]) {
                gameBoard[index] = currentPlayer;
                renderBoard();
                if (!checkWinner()) {
                    currentPlayer = currentPlayer === "X" ? "O" : "X";
                }
            }
        }
        
        function renderBoard() {
            board.innerHTML = "";
            gameBoard.forEach((cell, index) => {
                const cellDiv = document.createElement("div");
                cellDiv.classList.add("cell");
                if (cell) cellDiv.classList.add("taken");
                cellDiv.innerText = cell;
                cellDiv.onclick = () => makeMove(index);
                board.appendChild(cellDiv);
            });
        }
        
        function resetGame() {
            gameBoard = ["", "", "", "", "", "", "", "", ""];
            currentPlayer = "X";
            message.innerText = "";
            renderBoard();
        }
        
        renderBoard();
    </script>
</body>
</html>
