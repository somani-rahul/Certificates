<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #282c34;
            overflow: hidden;
            font-family: Arial, sans-serif;
        }

        .welcome-container {
            text-align: center;
            color: white;
        }

        .welcome-title {
            font-size: 3em;
            animation: fadeIn 2s ease-in-out, moveUp 2s ease-in-out;
        }

        .welcome-subtitle {
            font-size: 1.5em;
            animation: fadeIn 3s ease-in-out, moveUp 3s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes moveUp {
            from {
                transform: translateY(50px);
            }
            to {
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="welcome-container">
        <div class="welcome-title">Welcome to Our Website!</div>
        <div class="welcome-subtitle">We're glad to have you here.</div>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const title = document.querySelector('.welcome-title');
            const subtitle = document.querySelector('.welcome-subtitle');
            
            setTimeout(() => {
                title.classList.add('show');
            }, 1000);
            
            setTimeout(() => {
                subtitle.classList.add('show');
            }, 2000);
        });
    </script>
</body>
</html>


# Contents of Readme:
## Domain Certificate
## Academic Result
## Other Certificates Information Alltogether

# My astonishing performances
### Completed six courses by IITs finishing Programming Domain:
![NPTEL Domain - Programming](Compressed_Certificates/NPTEL_DOMAIN_CERTIFICATE.jpg)

### Latest Academic Result: 
![fourth_sem_result.jpg](Compressed_Certificates/fourth_sem_result.jpg)

### All other courses: 
| Name                                       | Score | Date of certification | Institution      |
| :----------------------------------------: | :---: | :-------------------: | :--------------: |
| Programming in Java                        | 90    | October,2022          | IIT Kharagpur    |
| An Introduction to Programming through CPP | 85    | April,2022            | IIT Bombay       |
| Programming and DSA using Python           | 78    | March, 2023           | IIT Madras       |
| Introduction to IOT                        | 85    | October, 2023         | IIT Kharagpur    |
| Cloud Computing                            | 72    | April, 2023           | IIT Kharagpur    |
| Database Management System                 | 69    | September, 2023       | IIT Kharagpur    |