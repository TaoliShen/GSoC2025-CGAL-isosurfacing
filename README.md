# Google Summer of Code 2025 – CGAL Isosurfacing  
## Enhanced Dual Contouring for Manifold Isosurfacing

This repository documents my **Google Summer of Code 2025** project with **CGAL (GeometryFactory)**,
focused on the design and implementation of **Enhanced Dual Contouring** algorithms
for **topologically correct, manifold isosurfacing**.

The work extends CGAL’s existing isosurfacing pipeline by addressing ambiguous
configurations and nonmanifold artifacts that arise in standard isosurfacing methods (Marching Cubes, Dual Contouring, etc)

---

## Project overview

Key contributions of this project include:

- Implementation of enhanced Dual Contouring algorithms
- Integration of topologically correct handling of ambiguous Marching Cubes cases
- Identification and resolution of nonmanifold edge configurations arising from
  tunnel-like structures
- Graph-based post-processing strategies inspired by
  Zint–Grosso–Gürtler–style methods
- Improved robustness and manifold guarantees for CGAL’s dual isosurfacing pipeline

---

## Main resources

- 📌 **Project issue / design discussion**  
  https://github.com/CGAL/cgal/issues/9047

- 🔧 **Development branch (full implementation)**  
  https://github.com/CGAL/cgal-public-dev/tree/gsoc2025-Isosurfacing_EDC-tshen

- 📄 **Final technical report**  
  `final_report.md`

---

## Code locations

The work is located within the `Isosurfacing_3` package on the
development branch:

- `Isosurfacing_3/include/` – core algorithms  
- `Isosurfacing_3/src/` – implementation details and helper routines  
- `Isosurfacing_3/examples/` – example usage 

Please refer to the project issue and the final technical report for detailed
explanations of algorithmic design decisions and implementation details.

---

## Development notes

During the course of the project, I maintained a detailed internal development log
documenting experiments, debugging efforts, algorithmic decisions, and intermediate
results. The publicly available materials in this repository present a curated and
self-contained summary of the final implementation and results.

---

## Mentorship

This work was conducted as part of **Google Summer of Code 2025** with **CGAL / GeometryFactory** under the mentorship of Mael Rouxel-Labbé, Sven Oesau, and Pierre Alliez. 
