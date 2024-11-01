Here's an updated `README.md` file that includes the use of SQL to store Firebase URLs and retrieve them in the profile section:


# Template Creator

This application allows users to create and customize templates, download their creations, and save them in their profile. Each saved creation's download link is stored in an SQL database and can be accessed anytime.

## How It Works

1. **Choose Your Template**
   - Start by browsing the available templates in the application.
   - Select a template that fits your needs, designed to be easily customizable.

2. **Customize According to Your Needs**
   - Modify the selected template to match your preferences.
   - Adjust text, colors, fonts, and other styling options.
   - Personalize the layout and content to create the perfect design.

3. **Download Your Creation**
   - Once you're satisfied with the customization, download your creation.
   - A high-quality file will be generated for download.

4. **Save and Access Later in Profile**
   - Save your creation’s download link to your profile for future access.
   - Each download link is securely stored in an SQL database along with the user's Firebase URL.
   - Access saved templates anytime by visiting the profile section, where saved designs can be viewed or re-downloaded.

## Features

- A variety of template designs to choose from
- User-friendly customization options
- High-quality downloads of completed designs
- Secure storage of download links in SQL database
- Profile section for managing and re-accessing saved creations

## Technical Details

- **SQL Database**: The application uses SQL to store each user's Firebase download URL associated with their profile. This enables efficient storage and retrieval of saved designs.
- **Firebase Storage**: Generated designs are uploaded to Firebase, and the URL is saved in the SQL database. This allows users to download or re-download their creations directly from their profile.
  
## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/template-creator.git
   ```

2. Navigate into the project directory:
   ```bash
   cd template-creator
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up your **SQL Database**:
   - Configure the SQL database to store user data and Firebase URLs.
   - Update the database connection settings in your configuration file.

5. Configure **Firebase**:
   - Set up Firebase for file storage.
   - Update Firebase configuration details in the application.

6. Start the application:
   ```bash
   npm start
   ```

7. Open the app in your browser:
   ```
   http://localhost:3000
   ```

## Database Structure

- **Users Table**: Stores user information, including IDs, profile details, and any associated Firebase URLs for saved templates.
- **Templates Table**: Stores the details of saved templates and download URLs linked to user profiles.

