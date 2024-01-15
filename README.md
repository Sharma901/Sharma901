
from PIL import Image, ImageDraw, ImageFont

# Create a blank image with a white background
width, height = 400, 400
image = Image.new("RGB", (width, height), "white")

# Load a font
font = ImageFont.load_default()

# Create a drawing object
draw = ImageDraw.Draw(image)

# Define the text and position
text = "Ayus Adhikari"
text_position = ((from PIL import Image, ImageDraw, ImageFont

# Create a blank image with a white background
width, height = 400, 400
image = Image.new("RGB", (width, height), "white")

# Load a font
font = ImageFont.load_default()

# Create a drawing object
draw = ImageDraw.Draw(image)

# Define the text and position
text = "Ayus Adhikari"
text_position = ((width - draw.textsize(text, font)[0]) // 2, height // 2)

# Add text to the image
draw.text(text_position, text, fill="black", font=font)

# Save the image
image.save("robot_ayus_adhikari.png")

# Display the image
image.show()[0]) // 2, height // 2)

# Add text to the image
draw.text(text_position, text, fill="black", font=font)

# Save the image
image.save("robot_ayus_adhikari.png")

# Display the image
image.show()
