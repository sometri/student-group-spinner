# Student Group Spinner - Complete User Guide

## 📋 **Overview**
The Student Group Spinner is a web-based application that helps educators create random student groups using an interactive spinning wheel. It features a comprehensive dashboard for managing students, configuring groups, and visualizing results.

## 🎯 **Quick Start Guide**

### **Step 1: Access the Application**
1. Save the HTML code as `student-group-spinner.html`
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No installation or internet connection required after saving

### **Step 2: Add Students**
You have **three ways** to add students:

#### **Method A: Manual Entry**
1. Type a student's name in the text box under "Student List"
2. Press **Enter** or click the **"Add"** button
3. Repeat for all students

#### **Method B: File Upload**
1. Click **"Browse Files"** in the upload area or drag & drop a file
2. **Supported formats**: `.txt`, `.csv`
3. **File format options**:
   - One student per line:
     ```
     Alice Johnson
     Bob Smith
     Carol Davis
     ```
   - Comma-separated:
     ```
     Alice Johnson, Bob Smith, Carol Davis
     ```

#### **Method C: Sample Students**
1. Click **"Add Sample Students"** for a quick list of 16 sample names
2. Useful for testing the application

### **Step 3: Configure Groups**

#### **Group Size Options:**
- **Fixed size**: Choose 2-6 students per group
- **Custom**: Select "Custom (use group count)" to define only the number of groups

#### **Number of Groups:**
- **Auto-calculate**: Automatically calculates based on student count and group size
- **Fixed number**: Choose 2-8 groups (extra options available)

#### **Distribution Method** (for uneven student counts):
1. **Evenly Distribute** (Default): Spreads extra students across first groups
2. **Fill First Groups**: Prioritizes filling earlier groups completely
3. **Fill Last Groups**: Prioritizes filling later groups completely

### **Step 4: Generate Groups**
1. Click the **"Spin the Wheel"** button
2. Watch the animated wheel spin for 3 seconds
3. View automatically generated groups in the results section

## 🎡 **Using the Spinning Wheel**

### **Visual Features:**
- **Color-coded segments**: Each student gets a unique color
- **Student names**: Displayed on their respective segments
- **Center pointer**: Indicates the starting position
- **Smooth animation**: With realistic physics simulation

### **Wheel Behavior:**
- Spins for 5 full rotations plus a random final position
- Animation slows down realistically (easing effect)
- Results appear immediately after spinning stops

## 📊 **Understanding Results**

### **Group Display:**
- **Group cards**: Each group shown in a separate box
- **Member list**: All students in the group listed
- **Group size**: Number displayed in a colored circle
- **Uneven groups**: Highlighted with red border and background

### **Interpreting Uneven Groups:**
When student count doesn't divide evenly:

#### **Scenario**: 14 students, 4 groups
- **Even Distribution**: Groups of 4, 4, 3, 3
- **Fill First**: Groups of 4, 4, 3, 3
- **Fill Last**: Groups of 3, 3, 4, 4

**Visual indicators**:
- ✅ Even groups: Blue border
- ⚠️ Uneven groups: Red border with light red background
- Summary message explains the distribution

## 💾 **Data Management**

### **Automatic Saving:**
- All data automatically saves to your browser's local storage
- Students, groups, and settings persist between sessions
- No manual saving required

### **Manual Actions:**

#### **Clear Students:**
1. Click **"Clear All"** button
2. Confirm the action when prompted
3. ⚠️ This action cannot be undone

#### **Reset Groups:**
1. Click **"Reset Groups"** button
2. Removes all generated groups
3. Does not affect student list

## 📤 **Export Features**

### **Export Groups:**
1. Click **"Export Groups"** button
2. Downloads a `.txt` file with:
   - Generation date and time
   - Total student count
   - Number of groups
   - Distribution method used
   - Complete group lists with member names
   - Summary of uneven groups (if applicable)

### **Export Student List:**
1. Click **"Export Student List"** button
2. Downloads a `.txt` file with:
   - Export date and time
   - All students numbered sequentially

## 🔧 **Advanced Features**

### **Managing Individual Students:**

#### **Remove a Student:**
1. Find the student in the list
2. Click the **red "×"** button next to their name
3. Student is immediately removed

#### **Edit Student List:**
- **Add**: Use the input field or file upload
- **Remove**: Click individual remove buttons
- **Clear**: Use "Clear All" for complete reset

### **File Upload Details:**

#### **Best Practices:**
1. **File encoding**: Use UTF-8 for special characters
2. **Name format**: Firstname Lastname (recommended)
3. **Duplicate handling**: Duplicate names are automatically filtered

#### **Troubleshooting Uploads:**
- **Empty file**: Shows error notification
- **Unsupported format**: Only TXT/CSV accepted
- **Large files**: Processed efficiently (no practical limit)

### **Distribution Method Scenarios:**

#### **Class of 17 students, 5 groups:**
- **Evenly**: 4, 4, 3, 3, 3
- **First Groups**: 4, 4, 3, 3, 3
- **Last Groups**: 3, 3, 3, 4, 4

#### **When to use each method:**
- **Evenly**: General purpose, balanced approach
- **First Groups**: When first groups need to be complete for activities
- **Last Groups**: When later groups need full teams for competitions

## 📱 **Mobile & Responsive Use**

### **Mobile Features:**
- **Adaptive layout**: Adjusts for different screen sizes
- **Touch-friendly**: All buttons optimized for touch
- **Vertical stacking**: On small screens, sections stack vertically

### **Screen Size Adaptation:**
- **Large screens**: Side-by-side wheel and dashboard
- **Medium screens**: Adjusted wheel size
- **Small screens**: Single column layout

## 🔔 **Notifications & Feedback**

### **Notification Types:**
- **Success** (Green): Actions completed successfully
- **Error** (Red): Something went wrong, action needed
- **Info** (Blue): Informational messages

### **Common Notifications:**
- "Added X students from file"
- "Created X groups successfully!"
- "Not enough students for the selected number of groups"
- "Loaded X students from previous session"

## 💡 **Pro Tips**

### **For Classroom Use:**
1. **Prepare in advance**: Upload student list before class
2. **Save time**: Use sample students for demonstration
3. **Multiple rounds**: Reset groups and spin again for different combinations
4. **Export records**: Save group lists for attendance or grading

### **Technical Tips:**
1. **Browser choice**: Chrome or Firefox for best performance
2. **File backup**: Export student list as backup
3. **Printing**: Use browser's print feature for group lists
4. **Fullscreen**: Press F11 for better visibility during demonstrations

## 🛠 **Troubleshooting**

### **Common Issues:**

#### **Wheel Not Spinning:**
- Check if students are added
- Ensure "Spin the Wheel" button is not disabled
- Refresh the page if unresponsive

#### **File Not Uploading:**
- Verify file format (.txt or .csv)
- Check file encoding (use plain text)
- Ensure file is not empty

#### **Groups Not Generating:**
- Verify student count ≥ group count
- Check distribution method selection
- Try resetting and spinning again

#### **Data Not Saving:**
- Check browser settings (local storage enabled)
- Try different browser
- Export data before clearing browser cache

### **Browser Compatibility:**
- **Fully supported**: Chrome 60+, Firefox 55+, Edge 79+, Safari 11+
- **Partially supported**: Older browsers may lack some animations
- **Not supported**: Internet Explorer

## 🔄 **Workflow Examples**

### **Example 1: Quick Group Creation**
1. Click "Add Sample Students"
2. Set "Group Size" to 4
3. Click "Spin the Wheel"
4. Export groups if needed

### **Example 2: Custom Distribution**
1. Upload student list from file
2. Set "Number of Groups" to 5
3. Select "Fill Last Groups" distribution
4. Spin and review uneven groups
5. Adjust if needed

### **Example 3: Repeated Use**
1. Load previous session (automatic)
2. Modify student list if needed
3. Change group configuration
4. Generate new groups
5. Export both student list and groups

## 📚 **Educational Applications**

### **Classroom Uses:**
- **Group projects**: Random, unbiased team creation
- **Discussion groups**: Mix students for diverse perspectives
- **Peer review**: Assign reviewers randomly
- **Seating arrangements**: Create new seating groups

### **Benefits:**
- **Fairness**: Eliminates teacher bias in group creation
- **Efficiency**: Saves time compared to manual grouping
- **Flexibility**: Multiple configuration options
- **Transparency**: Visual process students can see
- **Record keeping**: Export for documentation

## ⚙️ **Technical Details**

### **Data Storage:**
- **Location**: Browser's local storage
- **Capacity**: Typically 5-10MB per domain
- **Access**: Only from same browser on same device

### **Performance:**
- **Student limit**: Practical limit of 100+ students
- **Group limit**: Up to 8 groups (configurable)
- **Animation**: 60fps smooth spinning

### **Security & Privacy:**
- **Local processing**: All data stays on your computer
- **No internet**: Works completely offline
- **No tracking**: No analytics or data collection
- **Export control**: You control what gets exported

## 🆘 **Getting Help**

### **Built-in Help:**
- Tooltips and labels throughout interface
- Clear error messages with suggestions
- Visual indicators for all actions

### **Quick Reference:**
- **Add students**: Text input or file upload
- **Configure**: Set group size/count and distribution
- **Generate**: Click spin button
- **Export**: Download results for records

---

**Note**: This application works entirely in your browser. No data is sent to any server, making it ideal for privacy-conscious educational environments. All features are available offline once the file is downloaded.
