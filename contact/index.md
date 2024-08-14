---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are always excited to explore new opportunities for collaboration and welcome talented individuals who are passionate about advancing research to join our lab. If you are interested in discussing potential projects, partnerships, or becoming a part of our dynamic team, please reach out to us. 

{%
  include button.html
  type="email"
  text="pmcnutt@wakehealth.edu"
  link="pmcnutt@wakehealth.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/cURHwRQKUkoep2JZ8"
%}

{% include section.html %}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Maps Static API Example</title>
    <style>
        #map {
            width: 100%;
            height: 500px;
        }
    </style>
</head>
<body>
    <h1>Google Maps Static API Example</h1>
    <div id="map"></div>

  <script>
        function displayMap(address) {
            const mapUrl = `https://www.google.com/maps/place/Wake+Forest+Institute+for+Regenerative+Medicine/@36.0948107,-80.2399591,3a,75y,90t/data=!3m8!1e2!3m6!1sAF1QipPzwvDXWv9jBnfhoZyfTapslSju1daU_UR_9ZI3!2e10!3e12!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipPzwvDXWv9jBnfhoZyfTapslSju1daU_UR_9ZI3%3Dw114-h86-k-no!7i4032!8i3024!4m7!3m6!1s0x8853ae5bad1c264b:0x698389952d5975bf!8m2!3d36.0948107!4d-80.2399591!10e5!16s%2Fg%2F1q2wlm40s?entry=ttu`;

            document.getElementById('map').innerHTML = `<img src="${mapUrl}" alt="Google Map">`;
        }
        
        displayMap('391 Technology Way NE, Winston-Salem, NC 27101');
    </script>
</body>
</html>

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption=""
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption=""
%}

{% endcapture %}

