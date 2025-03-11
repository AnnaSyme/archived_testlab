Welcome to the Galaxy {{ site_name }} {{ lab_name }}! 



<!-- example grid system with links, 

note that many of the sections here are not yet actual sections as yml files, just here for examples

to link to a section, see what it is called in the yml file (it's id, on the first line)
then add Section, so data becomes dataSection

-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap Grid</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: white; /* White background */
        }
        .grid-item {
            background-color: #cce5ff; /* Light blue */
            border-radius: 10px; /* Rounded corners */
            padding: 15px; /* Slightly reduced padding */
            text-align: center;
            font-size: 1em; /* Slightly smaller font */
            font-weight: bold;
            transition: 0.3s;
        }
        .grid-item a {
            text-decoration: none;
            color: #0056b3;
            display: block;
        }
        .grid-item:hover {
            background-color: #99c2ff; /* Darker blue on hover */
        }
    </style>
</head>
<body>

<div class="container mt-3">
    <div class="row mt-3">
        <div class="col-md-3"><div class="grid-item"><a href="#importSection">Import Data</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#dataSection">Quality Control</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#wholeExome">Whole Exome</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#genomeAssembly">Genome Assembly</a></div></div>
    </div>
    <div class="row mt-3">
        <div class="col-md-3"><div class="grid-item"><a href="#phylogenetics">Phylogenetics</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#snpCalling">SNP Calling</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#ecology">Ecology</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#microbiology">Microbiology</a></div></div>
    </div>
    <div class="row mt-3">
        <div class="col-md-3"><div class="grid-item"><a href="#rnaSeq">RNA-seq</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#transcriptomics">Transcriptomics</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#galaxyHelp">Galaxy Help</a></div></div>
        <div class="col-md-3"><div class="grid-item"><a href="#contactAgrf">Contact AGRF</a></div></div>
    </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



<!-- older formatting test for links, note 
to link to a section, see what it is called in the yml file (it's id, on the first line)
then add Section, so data becomes dataSection
note that many of the sections here are not yet actual sections as yml files, just here for examples
-->
<!-- 
<h4 class="mb-3">What's in the lab?</h4>
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
        Scroll down, or click here to see all topics:
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <div class="row">
          <div class="col-md-3">
            <a href="#importSection" style="color: blue; text-decoration: underline;">Import Data</a>
          </div>
          <div class="col-md-3">
            <a href="#dataSection" style="color: blue; text-decoration: underline;">Quality control</a>
          </div>
          <div class="col-md-3">
            <a href="#wholeExome" style="color: blue; text-decoration: underline;">Whole Exome</a>
          </div>
          <div class="col-md-3">
            <a href="#genomeAssembly" style="color: blue; text-decoration: underline;">Genome Assembly</a>
          </div>
          <div class="col-md-3">
            <a href="#phylogenetics" style="color: blue; text-decoration: underline;">Phylogenetics</a>
          </div>
          <div class="col-md-3">
            <a href="#snpCalling" style="color: blue; text-decoration: underline;">SNP Calling</a>
          </div>
          <div class="col-md-3">
            <a href="#ecology" style="color: blue; text-decoration: underline;">Ecology</a>
          </div>
          <div class="col-md-3">
            <a href="#microbiology" style="color: blue; text-decoration: underline;">Microbiology</a>
          </div>
          <div class="col-md-3">
            <a href="#rnaSeq" style="color: blue; text-decoration: underline;">RNA-seq</a>
          </div>
          <div class="col-md-3">
            <a href="#transcriptomics" style="color: blue; text-decoration: underline;">Transcriptomics</a>
          </div>
          <div class="col-md-3">
            <a href="#galaxyHelp" style="color: blue; text-decoration: underline;">Galaxy Help</a>
          </div>
          <div class="col-md-3">
            <a href="#contactAgrf" style="color: blue; text-decoration: underline;">Contact AGRF</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
-->