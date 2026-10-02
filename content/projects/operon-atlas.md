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

OperonAtlas is a large-scale bioinformatics resource for exploring computationally predicted operons across more than **21,000 bacterial genomes** and nearly **90 million genes**. 

The project involved processing genome annotations at scale and constructing text representations of neighboring gene pairs from genomic features. A RoBERTa-based transformer model was then used to perform operon inference across the full genome collection, with the resulting predictions processed into searchable operons for interactive exploration through the web platform.

The web platform allows users to:

- **Search predicted operons and gene families** across thousands of bacterial genomes.
- **Browse individual genomes** and inspect their predicted operon organization.
- **Visualize operon structures** and the genes contained within each prediction.
- **Compare operon families across genomes** to examine their occurrence and organization.
- **Explore biological annotations** associated with genes and operon families.
- **Download prediction data** for further analysis.

The production system is deployed entirely on **Cloudflare**, using **Pages** for the frontend, **Workers** for the API, **D1** for structured queryable data, and **R2** for larger downloadable datasets. The frontend is implemented in HTML, CSS, and JavaScript, while the underlying data and inference pipelines were developed primarily in Python.

The resource is publicly available at **[operonatlas.org](https://operonatlas.org)**.