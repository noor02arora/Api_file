"# Api_file" 
# File Information Web Server

This is a simple REST API-based web server that accepts file uploads and provides information about the uploaded files.

## API Endpoints

### Upload File
Upload a file and receive information about the file.

- **URL:** `/upload`
- **Method:** `POST`
- **Request:**
  - Form Data: `file` (file to upload)
- **Response:**
  - JSON Object with file information

## Running the Server

To run the web server locally, follow these steps:

1. Install Python and Flask.
2. Clone this repository.
3. Navigate to the project directory.
4. Run `python app.py`.
5. Access the server at http://127.0.0.1:5000.

## Testing the API

You can test the API using tools like `curl`, Postman, or a web browser. For example:

- Using curl:
  ```bash
  curl -X POST -F "file=@path/to/your/file.txt" http://127.0.0.1:5000/upload

  ## Using the UI

You can also use the provided UI to upload files and view information about them.

1. Make sure the server is running (follow the instructions in the "Running the Server" section).
2. Access the UI by visiting [http://127.0.0.1:5000](http://127.0.0.1:5000) in your web browser.
3. Use the UI to upload files and view their information.


 
