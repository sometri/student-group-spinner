📋 Table of Contents
Overview

Features

Quick Start

Detailed Guide

Adding Students

Configuring Groups

Using the Wheel

Understanding Results

Exporting Data

Advanced Features

Troubleshooting

About the Creator

Technical Details

🎯 Overview
The Student Group Spinner is a web-based application designed for educators to create random, fair student groups quickly and efficiently. With its interactive spinning wheel and comprehensive dashboard, it transforms the group creation process into an engaging, visual experience.

Perfect for: Classroom teachers, workshop facilitators, team leaders, and anyone needing to create balanced groups.

✨ Features
✅ Interactive Spinning Wheel - Visual, animated wheel with color-coded segments
✅ Multiple Student Entry Methods - Manual entry, file upload, or sample data
✅ Smart Group Distribution - Three methods for handling uneven student counts
✅ File Upload Support - Import student lists from TXT/CSV files
✅ Data Persistence - Automatically saves your work between sessions
✅ Export Capabilities - Download groups and student lists as text files
✅ Responsive Design - Works on desktop, tablet, and mobile devices
✅ No Installation Required - Runs directly in your web browser
✅ Completely Offline - All processing happens on your computer
✅ Professional UI - Clean, modern interface with helpful notifications

🚀 Quick Start Guide
Step 1: Launch the Application
Download the student-group-spinner.html file

Double-click to open in any modern browser (Chrome, Firefox, Edge, Safari)

No internet connection required after initial load

Step 2: Add Students (Choose One Method)
Type names: Enter names in the text box and click "Add"

Upload file: Drag & drop a TXT/CSV file with student names

Use samples: Click "Add Sample Students" for instant demo data

Step 3: Configure Groups
Set Group Size (2-6 students or Custom)

Choose Number of Groups (Auto-calculate or specific number)

Select Distribution Method for uneven counts

Step 4: Generate Groups
Click the "Spin the Wheel" button

Watch the animated wheel spin (3 seconds)

View automatically generated groups

Step 5: Save Results
Export Groups: Download groups as a text file

Export Student List: Save your student roster

Print: Use browser's print function for hard copies

📚 Detailed Guide
Adding Students
Method 1: Manual Entry
Locate the "Student List" section in the dashboard

Type a student's name in the text input field

Press Enter or click the "Add" button

Repeat for all students

Tip: Use first and last names for clarity (e.g., "Alex Johnson" instead of just "Alex")

Method 2: File Upload
Supported file formats: .txt, .csv

File Format Examples:

Option A: One student per line

Oeng Sometri
Alice Johnson
Bob Smith
Carol Davis
David Wilson
Emma Brown
Option B: Comma-separated


Alice Johnson, Bob Smith, Carol Davis, David Wilson, Emma Brown
Upload Steps:

Click "Browse Files" or drag & drop your file

The system automatically parses and adds unique names

View upload confirmation with student count

Method 3: Sample Students
Click "Add Sample Students" for 16 pre-filled names

Great for testing and demonstration

Can be combined with your own students

Managing Your Student List
Remove a student: Click the red × button next to any name

Clear all students: Use the "Clear All" button (requires confirmation)

Student count: Always visible at the top of the list

Configuring Groups
Group Size Options
Fixed size (2-6): Each group will have approximately this many students

Custom: Ignores size, uses only the group count setting

Number of Groups
Auto-calculate: Calculates based on student count ÷ group size

Fixed number (2-8): Creates exactly this many groups

Distribution Methods
When student counts don't divide evenly:

Method	Description	Best For
Evenly Distribute	Spreads extra students across first groups	General classroom use
Fill First Groups	Prioritizes filling earlier groups completely	Activities where first groups need full teams
Fill Last Groups	Prioritizes filling later groups completely	Competitions where later groups need full teams
Example: 14 students, 4 groups

Evenly/Fill First: 4, 4, 3, 3

Fill Last: 3, 3, 4, 4

Using the Spinning Wheel
Visual Elements
Color-coded segments: Each student gets a unique color

Student names: Displayed on wheel segments (truncated if long)

Center pointer: Indicates the starting position

Spinning animation: 5 rotations with realistic physics

How It Works
The wheel spins for exactly 3 seconds

Uses easing for realistic deceleration

Results appear immediately after spinning stops

The visual spin is for engagement - groups are calculated instantly

Resetting
Reset Groups: Clears current groups for a new spin

Does not affect your student list

Understanding Results
Group Display
Each group appears in a card showing:

Group number (1, 2, 3, etc.)

Student count in a colored circle

List of all members

Visual indicators for uneven groups

Uneven Groups
When groups have different sizes:

Red border highlights uneven groups

Light red background for visual distinction

Summary message explains the distribution

Export includes uneven group notation

Interpreting Results
Blue border: Group has standard size

Red border: Group has extra students

Group count: Shows actual student count per group

Distribution summary: Explains how extra students were assigned

Exporting Data
Export Groups
Creates a comprehensive text file with:

Generation date and time

Total student count

Number of groups created

Distribution method used

Complete group lists with member names

Summary of uneven groups (if applicable)

File naming: student-groups-YYYY-MM-DD.txt

Export Student List
Creates a simple roster file with:

Export date and time

Total student count

Numbered list of all students

File naming: student-list-YYYY-MM-DD.txt

Printing
Use your browser's print function (Ctrl+P or Cmd+P):

Select "Save as PDF" for digital copies

Adjust margins for optimal formatting

Groups print in their card format

🔧 Advanced Features
Data Persistence
Automatic saving: All data saves to browser's local storage

Session recovery: Reopens with your last student list and settings

Browser-specific: Data stays in the browser where you saved it

Responsive Design
The application adapts to different screen sizes:

Screen Size	Layout	Wheel Size
Desktop	Side-by-side wheel and dashboard	500px
Tablet	Stacked layout	350-400px
Mobile	Single column	300px
Keyboard Shortcuts
Enter: Add student from input field

ESC: Close modal windows

Browser shortcuts: Ctrl+S (Save), Ctrl+P (Print)

Best Practices for Classroom Use
Before Class
Upload your student roster file

Test different group configurations

Export a backup of your student list

During Class
Project the application for full class visibility

Let students see the spinning wheel for engagement

Use "Spin Again" for multiple activities

After Class
Export groups for record-keeping

Reset for next session

Update student list for absences

File Management Tips
Keep backups: Export student lists regularly

File naming: Use consistent names (e.g., period1-students.csv)

Encoding: Use UTF-8 for special characters

Duplicates: The system automatically filters duplicate names

🛠 Troubleshooting
Common Issues & Solutions
Wheel Won't Spin
Check: Are students added? (Need at least 2)

Check: Is the spin button enabled? (Not grayed out)

Try: Refresh the page (F5) if unresponsive

File Won't Upload
Verify: File is .txt or .csv format

Check: File is not empty

Try: Different file encoding (use UTF-8)

Alternative: Copy-paste names manually

Groups Not Generating
Check: Student count ≥ desired group count

Verify: Distribution method is selected

Try: Different group size/number combination

Data Not Saving
Check: Browser supports localStorage

Try: Different browser (Chrome/Firefox recommended)

Export: Always export important data as backup

Display Issues
Refresh: Reload the page (F5)

Zoom: Reset browser zoom (Ctrl+0)

Browser: Update to latest version

Browser Compatibility
Browser	Status	Notes
Chrome	✅ Fully supported	Version 60+
Firefox	✅ Fully supported	Version 55+
Edge	✅ Fully supported	Version 79+
Safari	✅ Fully supported	Version 11+
Internet Explorer	❌ Not supported	Use modern browser
Performance Tips
Student limit: Works with 100+ students (practical limit)

Group limit: Up to 8 groups recommended

Animation: Disabled on very old devices

Storage: Clear browser cache if experiencing issues

👤 About the Creator
Your Name Here
Web Developer & Educator

https://profile.jpg

Contact Information
GitHub: @yourusername

LinkedIn: Your Name

Email: youremail@example.com

About This Project
This application was created to solve a common classroom challenge: creating fair, random student groups quickly and transparently. As an educator and developer, I wanted to combine engaging visuals with practical functionality.

Philosophy: Technology should make teaching easier, not more complicated. This tool exemplifies that principle by providing:

Simplicity: One-click group creation

Transparency: Visual process students can see

Flexibility: Multiple configuration options

Reliability: Works offline with no dependencies

Feedback & Contributions
I welcome your feedback and suggestions! Whether you've found a bug, have a feature request, or just want to share how you're using the tool, please reach out.

Ways to contribute:

Report issues or bugs

Suggest new features

Share your use cases

Translate to other languages

⚙️ Technical Details
Architecture
Frontend: HTML5, CSS3, JavaScript (ES6+)

Storage: Browser localStorage API

Graphics: HTML5 Canvas for wheel animation

Icons: Font Awesome 6.4.0

Fonts: System fonts (Segoe UI, fallbacks)

Data Flow
Input: Students added via UI or file upload

Processing: Random shuffle + distribution algorithm

Output: Visual groups + exportable text files

Storage: Automatic save to browser storage

Security & Privacy
Local processing: All data stays on your computer

No tracking: No analytics, cookies, or data collection

No server: Works completely offline

Export control: You decide what gets saved externally

File Structure

student-group-spinner.html    # Main application
README.md                     # This guide
profile.jpg                   # Creator profile picture (optional)
student-list.csv              # Example student file (optional)
Dependencies
Font Awesome CDN: Icons (loaded once)

No other external dependencies

Browser Storage Usage
Location: localStorage in your browser

Key: studentGroupSpinner

Data: JSON format with all application state

Size: Typically < 100KB

Clearing: Use browser settings or "Clear All" button

📖 Usage Examples
Example 1: Quick Classroom Groups

Scenario: 24 students, groups of 4
Steps:
1. Upload student list
2. Set Group Size: 4
3. Set Groups: Auto-calculate
4. Distribution: Evenly
5. Click Spin
Result: 6 groups of 4 students each
Example 2: Workshop Breakout Sessions

Scenario: 18 participants, 4 breakout groups
Steps:
1. Add participants manually
2. Set Group Size: Custom
3. Set Groups: 4
4. Distribution: Fill Last Groups
5. Click Spin
Result: Groups of 4, 4, 5, 5
Example 3: Team Projects

Scenario: 28 students, 6 project teams
Steps:
1. Use existing student list
2. Set Group Size: Custom
3. Set Groups: 6
4. Distribution: Fill First Groups
5. Click Spin
6. Export for project records
Result: Teams assigned with documentation
🔄 Update History
Version 1.0 (Current)
Initial release with all core features

Spinning wheel with animation

File upload support

Multiple distribution methods

Export functionality

Responsive design

About Me section

Planned Features
Custom color schemes

Group naming (instead of numbers)

Advanced export formats (Excel, PDF)

Student photos integration

Multiple class/period support

Attendance tracking integration

📞 Support
Getting Help
Check this guide - Most questions answered here

Browser console - Press F12 for error details

Contact creator - Use the About modal in the app

Common Questions
Q: Can I use this on multiple computers?
A: Yes, but student lists don't sync automatically. Export/import your list.

Q: Is there a mobile app?
A: Not currently, but the web version works perfectly on mobile browsers.

Q: Can I save different class lists?
A: Export each class list as a separate file and import as needed.

Q: Is my data secure?
A: Yes, all data stays on your computer. Nothing is sent to any server.

Q: Can I customize the colors?
A: Currently uses predefined colors. Customization planned for future updates.

📜 License & Attribution
Usage Rights
Free for educational use

Modification allowed for personal/classroom use

Commercial use requires permission

Attribution appreciated but not required

Third-Party Resources
Font Awesome: Icon library (CC BY 4.0)

Unsplash: Sample images (free to use)

Google Fonts: System font stack

Disclaimer
This software is provided "as-is" without warranty. The creator is not responsible for any issues arising from its use. Always keep backups of important data.

🎉 Get Started Now!
Download the HTML file

Open in your browser

Add your students

Configure your groups

Spin the wheel

Enjoy fair, random groups!

Happy Teaching! 🍎

Last Updated: $(date)
Version: 1.0
Creator: Your Name Here