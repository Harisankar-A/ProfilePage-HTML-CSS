# Profile Card

This repository contains an HTML document that displays a simple profile card. The card shows a profile picture, the name of the individual, and their professional roles.

## Features

- **Profile Information**: Displays a profile picture, name, and a list of professional roles.
- **Responsive Layout**: The card is centered both vertically and horizontally on the page, making it responsive to screen sizes.
- **Minimalistic Design**: Simple design with a circular image, a clean background, and clear typography.

## How It Works

### HTML Structure:
- **Profile Image**: A circular profile image (`img` tag), with the width and height set to 100px. The `border-radius` of 50% ensures that the image is displayed as a circle.
- **Profile Details**: Two headings are displayed below the profile image:
    - **Name**: An `h2` tag is used for the name of the individual.
    - **Roles**: An `h3` tag is used to display the individual's roles (e.g., Web Developer, Designer, App Developer).

### CSS Styling:
- **Container Layout**: The container (`div.con`) uses flexbox to center the content both vertically and horizontally. It has a beige background and rounded corners.
- **Profile Image**: The image is styled to be circular with a width and height of 100px, and its position is centered.
- **Typography**: The font used is the system font, making it look native to the user's device. The text is displayed clearly with no extra styling for a simple look.

## Technologies Used

- **HTML**: Structure for displaying the profile card.
- **CSS**: Styling for the profile card layout and image.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harisankar-A-18/BreadcrumbsProfilePage-HTML-CSS

    ```

2. Navigate to the project directory

3. Open the `index.html` file in your preferred web browser to view the profile card.

## Usage

- **Profile Display**: The page displays a profile card with the profile image, name, and roles.
- **Customization**: Replace the `src="profilejpeg"` with the path to your profile image and modify the text inside the `h2` and `h3` tags to reflect your details.


## Limitations

- **No Interactivity**: The card is static, with no interactive elements such as hover effects or buttons.
- **Placeholder Image**: The image source is currently a placeholder; ensure to add a valid image source.
