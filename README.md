# Anas Salah Ahmed

## iOS Developer

- 📞 **Phone:** 
  - (+20) <span id="phone">0</span>
- 📧 **Email:** [hello.anas07@gmail.com](mailto:hello.anas07@gmail.com)  
- 💼 **LinkedIn:** [anas-salah](https://www.linkedin.com/in/anas-salah)  
- 🌍 **Location:** Egypt, Cairo  

---

### About Me

I'm a passionate iOS Developer with extensive experience in mobile app development. I hold a 9-month diploma from ITI in Mobile Applications Development and have supplemented my learning with self-study via Harvard’s CS50. I'm committed to leveraging my skills to contribute to innovative projects and further my career in programming.

---

### Education

- **9-Month Diploma**, Professional Training Program (ITI)
  - *Specialization:* Native Mobile Applications Development
  - *Duration:* 10/2023 – 06/2024

- **Ain Shams University**
  - *Degree:* Bachelor of Commerce
  - *Duration:* 02/2018 – 05/2021
  - *Major:* Business Administration
  - *Grade:* Good

---

### Skills

- **iOS Development:** Swift, UIKit, SwiftUI, RxSwift, Combine, CocoaPods, Objective-C, Foundation, Cocoa Touch, Map Kit, Localization, Memory Management, Threading, Data Persistence, Core Data, Realm, SQLite, UserDefaults, Property Lists, Networking, Alamofire, URLSession, RESTful APIs, Unit Testing, Version Control System.
- **Android Development:** Kotlin, Java, Cross-Platform, Flutter.
- **Conceptual:** Problem Solving, Data Structures & Algorithms, OOP, Functional Programming, Architectural Design Patterns, Design Patterns, S.O.L.I.D. Principles, Clean Code, Firebase, Agile, UML, UI/UX Design.
- **Soft Skills:** Teamwork, Communication Skills.

---

<script>
  var phone = "(+20) 012-743-480-83";
  var phoneElement = document.getElementById("phone");
  var i = 3; // Start from the first digit of the phone number
  function typePhone() {
    if (phone[i] === '-') {
      // Display the dash immediately
      phoneElement.textContent += '-';
      i++;
    } else if (phone[i] === ' ') {
      // Display the space immediately
      phoneElement.textContent += ' ';
      i++;
    } else if (i < phone.length) {
      // Display the digit after a delay
      phoneElement.textContent += phone[i];
      i++;
      setTimeout(typePhone, 200); // Adjust the delay here if needed
    }
  }
  typePhone();
</script>
