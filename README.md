# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multiple Images Enlarge on Click</title>
<style>
  .clickable-image {
    width: 300px;
    height: auto;
    margin: 30px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .enlarged {
    transform: scale(2);
    z-index: 10;
    position: relative;
  }
</style>
</head>
<body>

<img class="clickable-image" src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-17 161827.png" alt="Image 1" />
<img class="clickable-image" src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-17 161924.png" alt="Image 2" />
<img class="clickable-image" src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-17 162049.png" alt="Image 3" />
<img class="clickable-image" src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-17 162236.png" alt="Image 4" />

<script>
  const images = document.querySelectorAll('.clickable-image');

  images.forEach(img => {
    img.addEventListener('click', () => {
      img.classList.toggle('enlarged');
    });
  });
</script>

</body>
</html>
```

## OUTPUT:
<img width="1920" height="1080" alt="528607934-737ba6e0-6cd9-407e-b050-dee93993ab05" src="https://github.com/user-attachments/assets/50aba680-15ea-4a3c-abd3-9b6bf36c649e" />
<img width="1920" height="1080" alt="528608048-ad2743f2-5e84-4ed3-aaef-905d8fcc414a" src="https://github.com/user-attachments/assets/d81e8f16-2fe6-490c-9142-e768b6c6435a" />
<img width="1920" height="1080" alt="528608105-e93615f7-8952-46bb-bc01-387d6f3f5fa0" src="https://github.com/user-attachments/assets/fc225e18-0a26-4e1a-bab7-4a9175018f0c" />
<img width="1920" height="1080" alt="528608159-3194731e-bed9-4235-b72b-44bfbb0a1f92" src="https://github.com/user-attachments/assets/6395a3ae-85da-45fd-96fd-97906d5584fd" />
<img width="1920" height="1080" alt="528608204-28a2f869-774d-4411-93dd-bba36634716f" src="https://github.com/user-attachments/assets/87ff7d70-3312-49d2-b22c-9132dd541ccc" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
