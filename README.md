# Google Review Feedback Form

A simple, responsive web form that collects customer feedback and redirects satisfied customers to leave Google reviews.

## Features

- ⭐ Interactive 5-star rating system with hover effects
- 📝 Feedback form for customers who rate 3 stars or below
- 🔗 Automatic redirect to Google Reviews for 4-5 star ratings
- 📊 Webhook integration for tracking clicks and collecting feedback
- 📱 Responsive design that works on all devices
- 🎨 Modern, clean UI with smooth animations

## How it Works

1. **Star Rating**: Customers click on stars to rate their experience (1-5 stars)
2. **High Ratings (4-5 stars)**: Automatically redirects to your Google Review page
3. **Low Ratings (1-3 stars)**: Shows a feedback form to collect detailed feedback
4. **Data Collection**: All interactions are tracked via webhooks for analytics

## Setup

1. **Configure URLs**: Update the following variables in `index.html`:
   - `GOOGLE_REVIEW_URL`: Your Google Reviews page URL
   - `FEEDBACK_WEBHOOK_URL`: Webhook URL for collecting feedback
   - `CLICK_TRACKER_WEBHOOK_URL`: Webhook URL for tracking clicks

2. **Deploy**: Upload the `index.html` file to your web server

## Customization

The form is fully customizable through CSS variables and JavaScript. You can:
- Change colors and styling
- Modify the feedback form text
- Add additional tracking parameters
- Customize the redirect behavior

## Usage

Simply include a `userId` parameter in the URL to track individual users:
```
https://yoursite.com/feedback-form.html?userId=12345
```

## Technologies Used

- HTML5
- CSS3 (with modern features like flexbox and transitions)
- Vanilla JavaScript (no dependencies)
- Responsive design principles

## License

This project is open source and available under the MIT License.
