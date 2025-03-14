# Form Registration

This project is a responsive registration form built using **HTML, Tailwind CSS, and JavaScript**. It allows users to enter their **general information** and **contact details**, then submit the form data to a backend API.

## Features
- **User-Friendly UI**: Clean and structured layout using Tailwind CSS.
- **Two Sections**:
  - **General Information**: Includes fields for title, first name, last name, position, company, business arena, and employees.
  - **Contact Details**: Includes fields for street, additional information, zip code, place, country, code, phone number, and email.
- **Terms and Conditions Checkbox**: Ensures users acknowledge terms before submission.
- **Submit Button**: Sends data to a backend API endpoint (`http://localhost:5000/api/forms`).
- **JavaScript Form Submission**: Uses `fetch()` to send form data in JSON format to the server.

## Technologies Used
- **HTML5**: For structuring the form.
- **Tailwind CSS**: For modern styling and responsiveness.
- **JavaScript (ES6)**: For handling form submission.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Ishemalove/LoveLink.git
   ```
2. Open the `index.html` file in a browser.
3. Fill in the required form fields.
4. Click **Register Badge** to submit the form.

## API Integration
Ensure you have a backend running at `http://localhost:5000/api/forms` to handle POST requests.

### Sample Request Body
```json
{
  "title": "Mr.",
  "firstName": "John",
  "lastName": "Doe",
  "position": "Manager",
  "company": "TechCorp",
  "businessArena": "IT",
  "employees": "500",
  "street": "123 Main St",
  "additionalInformation": "Suite 5",
  "zipCode": "10001",
  "place": "New York",
  "country": "USA",
  "code": "+1",
  "phoneNumber": "1234567890",
  "email": "john.doe@example.com"
}
```

## Future Improvements
- Add form validation.
- Implement success/error messages.
- Improve UI/UX with animations.
- Connect to a real backend service.

## License
This project is open-source and free to use.

