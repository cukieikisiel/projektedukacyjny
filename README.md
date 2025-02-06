# projektedukacyjny
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikacja do Zarządzania Projektami Edukacyjnymi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Aplikacja do Zarządzania Projektami Edukacyjnymi</h1>
        <nav>
            <ul>
                <li><a href="#dashboard">Dashboard</a></li>
                <li><a href="#tasks">Zarządzanie zadaniami</a></li>
                <li><a href="#communication">Komunikacja</a></li>
            </ul>
        </nav>
    </header>

    <section id="dashboard">
        <h2>Dashboard</h2>
        <div class="project-overview">
            <h3>Przegląd projektów</h3>
            <ul>
                <li>Projekt 1 - 50% ukończony</li>
                <li>Projekt 2 - 30% ukończony</li>
            </ul>
        </div>
        <div class="notifications">
            <h3>Powiadomienia</h3>
            <p>Brak nowych powiadomień.</p>
        </div>
    </section>

    <section id="tasks">
        <h2>Zarządzanie zadaniami</h2>
        <form id="task-form">
            <label for="task-name">Nazwa zadania:</label>
            <input type="text" id="task-name" name="task-name" required>
            
            <label for="assignee">Przypisz do:</label>
            <select id="assignee" name="assignee">
                <option value="user1">User 1</option>
                <option value="user2">User 2</option>
                <option value="user3">User 3</option>
            </select>
            
            <label for="deadline">Termin:</label>
            <input type="date" id="deadline" name="deadline" required>
            
            <button type="submit">Dodaj zadanie</button>
        </form>
        <div class="task-list">
            <h3>Lista zadań</h3>
            <ul>
                <li>Zadanie 1 - User 1 - Termin: 2024-12-20</li>
                <li>Zadanie 2 - User 2 - Termin: 2024-12-22</li>
            </ul>
        </div>
    </section>

    <section id="communication">
        <h2>Komunikacja</h2>
        <div class="chat">
            <h3>Czat grupowy</h3>
            <div class="chat-window">
                <p><strong>User 1:</strong> Cześć, jak idzie projekt?</p>
                <p><strong>User 2:</strong> Wszystko zgodnie z planem.</p>
            </div>
            <form id="chat-form">
                <input type="text" id="message" name="message" placeholder="Napisz wiadomość..." required>
                <button type="submit">Wyślij</button>
            </form>
        </div>
        <div class="file-sharing">
            <h3>Udostępnianie plików</h3>
            <form id="file-form">
                <input type="file" id="file" name="file" required>
                <button type="submit">Prześlij plik</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Aplikacja do Zarządzania Projektami Edukacyjnymi</p>
    </footer>
</body>
</html>
