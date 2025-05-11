
<style>
  * {
            margin: auto;
            padding: auto;
            box-sizing: border-box;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            margin-left: 2px;
            margin-right: 2px;
    }

        body {
            background-color: #f9f9f9;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            background-color: white;
            border-bottom: 1px solid #eaeaea;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .menu-title {
            font-size: 18px;
            font-weight: 600;
        }

        .close-btn {
            font-size: 24px;
            background: none;
            border: none;
            cursor: pointer;
        }

        .search-btn {
            font-size: 20px;
            background: none;
            border: none;
            cursor: pointer;
        }

        .nav-menu {
            list-style: none;
            width: 100%;
        }

        .nav-item {
            border-bottom: 1px solid #eaeaea;
        }

        .nav-link {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            text-decoration: none;
            color: #000;
            font-weight: 600;
            text-transform: uppercase;
            font-size: 14px;
            letter-spacing: 0.5px;
        }

        .dropdown-icon {
            font-size: 16px;
            transition: transform 0.3s ease;
        }

        .dropdown-icon.active {
            transform: rotate(180deg);
        }

        .dropdown-content {
            display: none;
            background-color: #f9f9f9;
            padding: 10px 20px;
        }

        .dropdown-content p {
            padding: 10px 0;
            color: #555;
            cursor: pointer;
        }

        .dropdown-content p:hover {
            color: #000;
        }

        .dropdown-content.show {
            display: block;
        }

        .nav-link:hover, .nav-link:focus {
            background-color: #f5f5f5;
        }

        .highlight {
    background-color: #f9f871;
    font-size: 0.9em;
    border-left: 3px solid orange;
    padding: 7px;
    font-weight: bold;
    width: 80%;
    margin: 0 auto;
  }

  h2, h1, {
    font-size: 1.5em;
    margin-bottom: 10px;
    text-align: center;
    background-color: #00d4db;
    font-family: rockwell;
    font-style: oblique;
  }

  h4, h3 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1.2em;
    margin-bottom: 5px;
    margin-top: 10px;
  }
  table {
      width: 80%;
      margin: 20px auto;
      border-collapse: collapse;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: center;
    }
    th {
      background-color: #4CAF50;
      color: white;
    }
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    tr:hover {
      background-color: #e0f7fa;
    }
    caption {
      caption-side: top;
      font-size: 1.5em;
      margin-bottom: 10px;
    }
    .answers{
        width: 80%;
        margin: 20px auto;
        border-collapse: collapse;
        font-family: Arial, sans-serif;
    }

    .submit-btn {
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1em;
    }

    .result {
      margin-top: 15px;
      font-weight: bold;
    }

    .dropbtn {
  background-color: #3498DB;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
  background-color: #2980B9;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  overflow: auto;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}
  </style>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>intermediate accounting</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="header">
        
        <div class="menu-title">Intermediate Accounting 2</div>
        
    </div>

    <ul class="nav-menu">
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                Prelims
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <nav id="navbar">
        <ul class="nav-list">
            <p><a class="nav-link active" href="#liabilities">Chapter 1: Liabilities</a></p>
            <p><a class="nav-link" href="#getting_started">Evidence of Knowledge of insufficient funds</a></p>
            <p><a class="nav-link" href="#authentication">duty of the drawer</a></p>
            <p><a class="nav-link" href="#endpoints">Credit Construed</a></p>
            <p><a class="nav-link" href="#request_examples">Elements of the Offense</a></p>
            <p><a class="nav-link" href="#error_handling">Defenses in BP 22</a></p>
         
        </ul>
    </nav>
            </div>
        </li>
        
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                Accounting Principles
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <p>Financial Accounting</p>
                <p>Managerial Accounting</p>
                <p>Taxation</p>
                <p>Auditing</p>
            </div>
        </li>
        
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                Case Studies
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <p>Finance Cases</p>
                <p>Management Cases</p>
                <p>Accounting Cases</p>
                <p>Business Ethics</p>
            </div>
        </li>
        
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                Study Materials
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <p>Lecture Notes</p>
                <p>Practice Exams</p>
                <p>Flashcards</p>
                <p>Study Guides</p>
            </div>
        </li>
        
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                Resources
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <p>Financial Calculators</p>
                <p>Formulas Reference</p>
                <p>Academic Journals</p>
                <p>Industry Reports</p>
            </div>
        </li>
        
        <li class="nav-item">
            <a href="#" class="nav-link" onclick="toggleDropdown(this)">
                About NCBA
                <span class="dropdown-icon">▼</span>
            </a>
            <div class="dropdown-content">
                <p>Faculty Directory</p>
                <p>Department Info</p>
                <p>Academic Calendar</p>
                <p>Contact Information</p>
            </div>
        </li>
    </ul>

<section class="content">
          <h1 id="">Intermediate Accounting 2</h1>
          <p>Welcome to the Intermediate Accounting 2 course. This course covers advanced topics in accounting, including financial reporting, analysis, and interpretation of financial statements.</p>
          <p>In this course, you will learn about:</p>
          <ul>
                <li>Advanced Financial Reporting</li>
                <li>Accounting for Income Taxes</li>
                <li>Accounting for Leases</li>
                <li>Accounting for Pensions and Other Postretirement Benefits</li>
                <li>Accounting for Share-Based Payments</li>
          </ul>        
</section>
<div>
    <section class="content">
        <h2 id="liabilities">Chapter 1: Liabilities</h2>
        <p>In this chapter, we will discuss the different types of liabilities, their recognition, measurement, and reporting in financial statements.</p>
        <p>Key topics include:</p>
        <ul>
            <li>Current vs. Non-current Liabilities</li>
            <li>Contingent Liabilities</li>
            <li>Long-term Debt</li>
            <li>Lease Obligations</li>
        </ul>
        <h3>Liabilities</h3>
        <p>Liabilities are obligations of an entity arising from past transactions or events, which are expected to result in an outflow of resources.</p>
        
        <p class="highlight">So basically saying it's the <strong>result</strong> of your <strong>past actions.</strong></p>
        
        <h4>Elements of liability:</h4>
        <ol>
            <li>Present obligation</li>
            <li>The obligation to <strong>transfer</strong> an economic resource</li>
            <li>The liability <strong>arises</strong> from the <strong>past</strong></li>
        </ol>
        
        
        
        <h4>They are classified into two main categories:</h4>
        <ul>
            <li><strong>Current Liabilities:</strong></li>

        <p>
            <ol>
                <li>The entity expects ti settke the liability within the entity's operating cycle.</li>
                <li>Holding the liability for the purpose of trading.</li>
                <li>The liability is due to be settled within twelve months after the reporting period.</li>
                <li>The Entity does not have the right at the end of the reporting period to defer settlement of the liability for atleast twelve months after the reporting period.</li>
            </ol>
        </p>
            <li><strong>Non-current Liabilities:</strong> If not current liabilities it must be non-current liabilities.</li>
        </ul>

        <h4>Measurements:</h4>
        <p >Measurement of current liabilities - <strong>FACE AMOUNT</strong></p>
        <p >Measurement of non-current liabilities - <strong>PRESENT VALUE</strong></p>
        <p>Current liabilities are usually settled within one year, while non-current liabilities are settled over a longer period.</p>
</section>

<section>
   <div class="quiz-container">
  <h2>Quick Quiz</h2>
  <form id="quizForm">
    <div class="question">
      <p>Problem 1-1<br>
    Gar Company reported the following liability account blances on December 31, 2024:</p>
    <table>
       <tr>
        <th>Account</th>
        <th>Amount</th>
        </tr>
        <tr>
        <td>Accounts Payable</td>
        <td>1,000,000</td>
        </tr>
        <tr>
        <td>Bonds payable, due december 31, 2026</td>
        <td>3,400,000</td>
        </tr>
        <tr>
            <td>Deferred tax liability</td>
            <td>200,000</td>
        </tr>
        <tr>
            <td>Dividends payable</td>
            <td>500,000</td>
        </tr>
        <tr>
            <td>Income tax payable</td>
            <td>900,000</td>
        </tr>
        <tr>
            <td>Notes payable, due December 31, 2025</td>
            <td>600,000</td>
        </tr>
    </table>
    <div class="answers">
      <p>What is the total amount of current liabilities?</p>
      <label><input type="radio" name="q1" value="a"> 7,100,000</label><br>
      <label><input type="radio" name="q1" value="b"> 2,000,000</label><br>
      <label><input type="radio" name="q1" value="c"> 3,900,000</label><br>
    </div>
    </div>
    <button class="submit-btn" onclick="checkAnswer()">Submit</button>

  <div class="result" id="result"></div>
  <div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Solution</button>
  <div id="myDropdown" class="dropdown-content">
    <p>Account payable
        Dividends payable
        Income tax payable
        Notes payable, due December 31, 2025</p>
    <p>Current liabilities = 1,000,000 + 500,000 + 900,000 + 600,000 = 3,900,000</p>
    </p>

 
</div>
<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>
<script>
  function checkAnswer() {
    const selected = document.querySelector('input[name="q1"]:checked');
    const result = document.getElementById('result');
    if (!selected) {
      result.textContent = "Please select an answer.";
      result.style.color = "orange";
    } else if (selected.value === "c") {
      result.textContent = "Correct! ✅";
      result.style.color = "green";
    } else {
      result.textContent = "Incorrect ❌ The correct answer is $2,500,000.";
      result.style.color = "red";
    }
  }
  
</script>
    <script>
        function toggleDropdown(element) {
            // Prevent default link behavior
            event.preventDefault();
            
            // Toggle the dropdown icon
            const icon = element.querySelector('.dropdown-icon');
            icon.classList.toggle('active');
            
            // Toggle the dropdown content
            const dropdownContent = element.nextElementSibling;
            dropdownContent.classList.toggle('show');
            
            // Close other dropdowns
            const allDropdowns = document.querySelectorAll('.dropdown-content');
            const allIcons = document.querySelectorAll('.dropdown-icon');
            
            allDropdowns.forEach(function(dropdown) {
                if (dropdown !== dropdownContent && dropdown.classList.contains('show')) {
                    dropdown.classList.remove('show');
                }
            });
            
            allIcons.forEach(function(dropIcon) {
                if (dropIcon !== icon && dropIcon.classList.contains('active')) {
                    dropIcon.classList.remove('active');
                }
            });
        }
    </script>

