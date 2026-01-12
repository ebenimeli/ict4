# Slides

<div class="glightbox" id="slides-container"></div>

<script>
  const totalSlides = 48;
  const basePath = "slides/unit01_inside_machine_part1/";
  const baseName = "unit01_inside_machine_part1.";

  const container = document.getElementById("slides-container");

  for (let i = 1; i <= totalSlides; i++) {
    const index = String(i).padStart(3, "0");

    const a = document.createElement("a");
    a.href = `${basePath}${baseName}${index}.jpeg`;
    a.className = "glightbox" + (i === 1 ? "" : " hidden");

    const img = document.createElement("img");
    img.src = a.href;
    img.alt = `Imagen ${i}`;

    a.appendChild(img);
    container.appendChild(a);
  }

  const lightbox = GLightbox({});
</script>
