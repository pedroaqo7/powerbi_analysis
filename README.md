[README.md](https://github.com/user-attachments/files/29577556/README.md)
# BI & Analytics Projects

A collection of Power BI dashboards and data analytics projects, covering the full workflow from data modeling to visual design and storytelling.

## About

This repository documents end-to-end BI projects, from raw data to finished dashboards. Each project includes the data model design, DAX measures, and the reasoning behind layout and chart choices, not just the final `.pbix` file.

## Structure

Each project lives in its own folder:

```
/project-name
  ├── README.md          # project-specific overview
  ├── model/             # TMDL export or documentation of the semantic model
  ├── layouts/            # SVG mockups used as background guides for report pages
  ├── measures.md         # DAX measures with explanations
  └── dashboard.pbix      # the Power BI file (if shareable)
```

## Approach

Every dashboard follows the same design principles:

- **Storytelling over grid layout** — pages are built to answer a specific business question and connect to the next, rather than being a flat collection of charts.
- **Grounded measures** — DAX is built directly from the semantic model, avoiding invented or approximate metrics.
- **Consistent visual language** — filter panel, KPI band, and chart areas follow the same structure across pages within a project, making reports easier to navigate.
- **Layout before build** — page layouts are prototyped as SVG mockups first (used as Power BI background images) to validate spacing and hierarchy before building the real visuals.

## Projects

| Project | Description |
|---|---|
| Sales Performance Dashboard | Outdoor/camping retail dataset — revenue, margin, product, and regional analysis

## Tech Stack

- **Power BI** (Desktop / Service)
- **DAX** for measures and calculated logic
- **Power BI Modeling MCP Server** for semantic model inspection and editing
- **SVG** for layout prototyping

## Author

Pedro — Analytics Engineer & BI Lead, based in São Paulo, Brazil.
