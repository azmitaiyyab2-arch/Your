# Video Streaming Platform

A full-featured video streaming website with upload functionality.

## Features
- Upload long videos (up to 2GB)
- Watch videos with a modern player
- Drag & drop upload interface
- Responsive design for all devices
- Video thumbnails
- Progress tracking during upload
- Sample videos included

## Installation

### Option 1: Static Version (Frontend Only)
1. Download all files
2. Open `index.html` in your browser
3. Upload functionality will be simulated

### Option 2: PHP Version
1. Install XAMPP/WAMP/MAMP
2. Place files in your web server directory
3. Import the SQL schema from upload.php comments
4. Update database credentials in upload.php
5. Access via `http://localhost/video-streaming-site`

### Option 3: Node.js Version
1. Install Node.js
2. Run `npm install`
3. Create MySQL database using schema in upload.php
4. Update database credentials in upload.js
5. Run `npm start`
6. Access via `http://localhost:3000`

## Configuration

### Database Setup
1. Create MySQL database named `videostream`
2. Create `videos` table (SQL in upload.php comments)
3. Update credentials in backend file

### File Upload Settings
- Maximum file size: 2GB
- Supported video formats: MP4, AVI, MOV, MKV, WEBM
- Supported thumbnail formats: JPG, PNG, GIF

## Security Considerations
1. Change default database credentials
2. Add user authentication
3. Implement file type validation
4. Add rate limiting
5. Use HTTPS in production
6. Store files outside web root
7. Add CSRF protection

## Deployment
For production deployment:
1. Use a cloud storage service (AWS S3, Google Cloud Storage)
2. Implement CDN for video delivery
3. Add caching mechanisms
4. Set up proper logging
5. Configure load balancing for high traffic
6. Implement video transcoding for multiple formats

## Technologies Used
- HTML5, CSS3, JavaScript
- PHP/Node.js for backend
- MySQL for database
- Express.js (Node.js version)
- Multer for file uploads

## License
MIT
