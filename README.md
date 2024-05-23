# Instagram Follower Automation

This project demonstrates how to automate the process of logging into Instagram, scrolling through followers, and following users using Python and Selenium.

## Description

The script logs into an Instagram account, navigates to a specified user's followers, scrolls through the list of followers, and follows those who are not already followed.

## Project Contents

The project includes the following file:

- `main.py`: Contains the Python script that performs the Instagram automation.

## How to Use

1. **Clone the repository:**
    ```sh
    git clone https://github.com/shad0wscr1pt3r/Instagram-Follower-Automation.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd Instagram-Follower-Automation
    ```
3. **Install the required packages:**
    ```sh
    pip install selenium
    ```
4. **Download and set up the ChromeDriver:** 
   - Ensure you have Chrome installed.
   - Download the ChromeDriver from [here](https://sites.google.com/chromium.org/driver/).
   - Place the ChromeDriver executable in a directory included in your system's PATH or in the project directory.

5. **Update your Instagram credentials in the script:**
    - Open `main.py`.
    - Replace `your_user` and `your_password` with your Instagram username and password.

6. **Run the script:**
    ```sh
    python main.py
    ```

## Customization

You can customize the script by adjusting the following parameters in the `main.py` file:

- **Instagram credentials:** Update the `user` and `paswd` variables with your Instagram username and password.
- **Followed accounts:** Modify the `sources` list with the Instagram usernames whose followers you want to follow.
- **Scroll duration:** Change the value in `scroll_followers(2)` to adjust the scrolling duration (in minutes).

## Project Structure

Instagram-Follower-Automation/
│
└── main.py

### `main.py`

The Python script contains functions to log in, navigate to followers, scroll through the follower list, and follow users.

## Author

Developed by Shad0wscr1pt3r.

---

© 2024 Shad0wscr1pt3r - All rights reserved.
