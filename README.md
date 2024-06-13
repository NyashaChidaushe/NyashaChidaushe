* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    text-align: center;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #ff6347;
}

.container {
    max-width: 1200px;
    margin: auto;
    overflow: hidden;
    padding: 0 2rem;
}

section {
    padding: 2rem 0;
}

section h2 {
    text-align: center;
    margin-bottom: 1rem;
    font-size: 2rem;
}

.service-list {
    display: flex;
    justify-content: space-between;
}

.service-item {
    background: #f4f4f4;
    padding: 1rem;
    border: 1px solid #ccc;
    transition: transform 0.3s ease;
}

.service-item:hover {
    transform: scale(1.05);
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

form label {
    font-weight: bold;
}

form input, form textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 0.7rem;
    background: #333;
    color: #fff;
    border: none;
    cursor: pointer;
    transition: background 0.3s ease;
}

form button:hover {
    background: #ff6347;
}

@media (max-width: 768px) {
    .service-list {
        flex-direction: column;
    }
}
