# timetable
# Class Schedule Web Application

A responsive web application for creating and managing your weekly class schedule with the ability to save your schedule locally and export it as a PDF.

## Features

- **Interactive Schedule Grid**: Input your classes for each time slot across Monday to Friday
- **Responsive Design**: Works on both desktop and mobile devices
- **Local Storage**: Saves your schedule automatically in your browser
- **PDF Export**: Generate a PDF version of your schedule with one click
- **Modern UI**: Clean, colorful interface with smooth animations

## How to Use

1. Open the `index.html` file in your web browser
2. Fill in your class names in the appropriate time slots
3. Click "Save Schedule" to store your schedule in your browser's local storage
4. Click "Generate PDF" to download your schedule as a PDF file

## Time Slots

The schedule includes these default time slots:
- 08:00 - 10:00
- 10:15 - 12:15
- 13:15 - 15:15
- 15:30 - 17:30

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and custom properties)
- JavaScript
- jsPDF library for PDF generation
- html2canvas library for capturing the schedule as an image
- Google Fonts (Poppins)

## Customization

You can easily customize:
- Time slots by editing the `timeSlots` array in the JavaScript
- Days of the week by editing the `days` array in the JavaScript
- Colors by modifying the CSS custom properties in the `:root` selector
- Styling in the CSS section

## Browser Compatibility

The application should work in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open-source and available for anyone to use or modify.

## Screenshot


## Future Enhancements

- Add weekend days
- Implement different color coding for different subjects
- Add reminder functionality
- Enable sharing schedules with others
- Add dark mode support

Enjoy organizing your class schedule!
