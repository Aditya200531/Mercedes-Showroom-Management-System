# Mercedes Showroom Management System

A comprehensive web application for managing a Mercedes showroom, featuring sales tracking, inventory management, customer reviews analysis, and AI-powered financial assistance.

## Features

### User Management
- **Role-based Access Control**
  - Admin: Full system access, staff management, analytics
  - Sales Staff: Order processing, customer management
  - Public: Car browsing, registration
- **Secure Authentication System**
  - Password hashing and encryption
  - Session-based authentication
  - Login/logout functionality
- **Staff Management**
  - Sales staff registration and approval workflow
  - Staff profile management
  - Performance tracking

### Sales & Inventory Management
- **Car Inventory System**
  - Add new car models with specifications
  - Update car details and availability
  - Delete discontinued models
  - Price management
- **Order Processing**
  - Order creation and tracking
  - Status updates (Pending, Approved, Delivered)
  - Order history and details
- **Sales Analytics**
  - Real-time sales dashboard
  - Monthly sales tracking
  - Revenue analysis
- **Sales Prediction**
  - Multiple ML models for accurate forecasting
  - Historical data analysis
  - Trend identification

### Analytics & Reporting
- **Sales Analysis**
  - Monthly sales breakdown
  - Year-over-year comparisons
  - Revenue tracking
- **Price Analysis**
  - Price segment categorization
  - Market positioning
  - Competitive analysis
- **Data Visualization**
  - Interactive charts and graphs
  - Customizable reports
  - Export functionality
- **Customer Review Analysis**
  - Sentiment analysis of reviews
  - Review categorization
  - Customer satisfaction metrics
- **Financial Analysis**
  - Document processing
  - Financial metrics calculation
  - Report generation

### AI Features
- **Financial AI Chatbot**
  - Document analysis and interpretation
  - Financial query answering
  - Report summarization
- **Sales Prediction Models**
  - Linear Regression: Basic trend analysis
  - Random Forest: Complex pattern recognition
  - LightGBM: High-performance gradient boosting
  - Prophet: Time series forecasting
- **Sentiment Analysis**
  - Customer review processing
  - Emotion detection
  - Feedback categorization
  - Automated response suggestions

## Tech Stack

- **Backend**: Python Flask
- **Database**: MongoDB
- **Frontend**: HTML, CSS, JavaScript
- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: scikit-learn, LightGBM, Prophet
- **Visualization**: Plotly
- **AI/ML**: Custom AI models for financial analysis and predictions

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd mercedes-showroom
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up MongoDB:
- Install MongoDB locally
- Create a database named 'mercedes_showroom'
- Update the MongoDB URI in `main.py` if needed

4. Run the application:
```bash
python main.py
```

## Usage

1. Access the application at `http://localhost:5000`
2. Default admin credentials:
   - Username: ADMIN
   - Password: ADMIN123

## Project Structure

```
├── main.py                 # Main application file
├── web_scrap/             # Web scraping utilities
├── templates/             # HTML templates
├── static/               # Static files (CSS, JS)
├── images/               # Image assets
├── financial_docs/       # Financial documents
├── data/                 # Data files
└── mercedes_docs/        # Mercedes documentation
```

## Security Features

- Password hashing
- Session management
- Role-based access control
- Protected routes

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please contact the development team. 
