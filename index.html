// index.html
<!DOCTYPE html>
<html>
<head>
    <title>Telegram Mini App Example</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/telegram-web-app/6.7.0/telegram-web-app.js"></script>
</head>
<body>
    <div id="app">
        <h1>My Telegram Mini App</h1>
        <button id="mainButton">Show Main Button</button>
        <button id="showPopup">Show Popup</button>
        <button id="themeData">Get Theme Data</button>
    </div>

    <script>
        // Initialize Telegram WebApp
        const webapp = window.Telegram.WebApp;

        // Expand to full height
        webapp.expand();

        // Enable closing confirmation
        webapp.enableClosingConfirmation();

        // Initialize main button
        const mainButton = webapp.MainButton;
        mainButton.setText("MAIN BUTTON");
        mainButton.onClick(() => {
            webapp.showAlert("Main button clicked!");
        });

        // Button handlers
        document.getElementById('mainButton').addEventListener('click', () => {
            if (mainButton.isVisible) {
                mainButton.hide();
            } else {
                mainButton.show();
            }
        });

        document.getElementById('showPopup').addEventListener('click', () => {
            webapp.showPopup({
                title: 'Example Popup',
                message: 'This is a popup message',
                buttons: [
                    {text: 'OK', type: 'ok'},
                    {text: 'Cancel', type: 'cancel'}
                ]
            });
        });

        document.getElementById('themeData').addEventListener('click', () => {
            const themeParams = webapp.themeParams;
            webapp.showAlert(
                `Theme: ${webapp.colorScheme}\n` +
                `Background: ${themeParams.bg_color}\n` +
                `Text: ${themeParams.text_color}`
            );
        });

        // Handle back button
        webapp.BackButton.onClick(() => {
            webapp.close();
        });
    </script>
</body>
</html>
