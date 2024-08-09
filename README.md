## 🔧 Environment Variables

- **PORT**: The port number on which the server will listen (default: `4000`).
- **MONGO_URI**: The MongoDB connection string for your database.
- **SECRET**: A secret key used for signing tokens.


## ⚠️ Troubleshooting

- Ensure that the `.env` file is correctly formatted and located in the root directory.
- Verify your MongoDB URI and credentials.
- Check for any error messages in the terminal and consult the logs for more details.

## 🛠️ Configuration

- `server.js`
- `.env`

## 📚 Usage

- API endpoints for creating, reading, updating, and deleting workout data.

## Create the .env File

In the root directory of your project, create a `.env` file with the following content:

## EXAMPLE
```env 
PORT=4000
MONGO_URI=mongodb+srv://<username>:<password>@<cluster-url>/<database>?retryWrites=true&w=majority
SECRET=example
