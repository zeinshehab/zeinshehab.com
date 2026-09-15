{
  "title": "OperonAtlas",
  "date": "2026-08-10",
  "link": "https://operonatlas.org",
  "image": "/img/operon_atlas.png",
  "description": "OperonAtlas is the largest-scale database of computationally predicted bacterial operons, spanning more than 21,000 bacterial genomes and nearly 90 million genes. It provides an interactive web platform for searching, visualizing, comparing, and downloading predicted operons.",
  "tags": [
    "Bioinformatics",
    "Machine Learning",
    "Data Engineering",
    "Python",
    "SQL",
    "JavaScript",
    "Cloudflare",
    "Cloudflare Workers",
    "D1",
    "R2"
  ],
  "fact": "",
  "featured": true,
  "weight": 50
}

OperonAtlas is a large-scale bioinformatics resource for exploring computationally predicted operons across more than **21,000 bacterial genomes** and nearly **90 million genes**. I developed the data processing and inference pipelines used to construct the atlas and built and deployed the accompanying web platform.

The project involved processing genome annotations at scale, running operon inference across the full bacterial genome collection, organizing predicted operons into searchable families, and transforming the resulting data into a form suitable for interactive exploration.

The web platform allows users to:

- **Search predicted operons and gene families** across thousands of bacterial genomes.
- **Browse individual genomes** and inspect their predicted operon organization.
- **Visualize operon structures** and the genes contained within each prediction.
- **Compare operon families across genomes** to examine their occurrence and organization.
- **Explore biological annotations** associated with genes and operon families.
- **Download prediction data** for further analysis.

The production system is deployed entirely on **Cloudflare**, using **Pages** for the frontend, **Workers** for the API, **D1** for structured queryable data, and **R2** for larger downloadable datasets. The frontend is implemented in HTML, CSS, and JavaScript, while the underlying data and inference pipelines were developed primarily in Python.

OperonAtlas grew out of my graduate research in machine learning and bioinformatics and combines several aspects of my work: large-scale biological data processing, machine-learning inference, database design, API development, cloud deployment, and scientific software development.

The resource is publicly available at **[operonatlas.org](https://operonatlas.org)**.