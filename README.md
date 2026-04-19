# Ancona Erasmus Lectures, April 2026

This repository collects the teaching materials for the courses taught in Ancona in April 2026. It contains the slide decks for two courses, together with related Gretl scripts and datasets used for classroom illustration and independent student work.

The material is intended as a compact companion to the lectures. It is therefore organized around examples rather than as a standalone software package.

## Course Materials

The repository includes two main slide decks:

- `slides/ancona_erasmus_forecasting_introduction.tex`: introduction to time-series forecasting, practical forecasting workflows, and model evaluation.
- `slides/machine_learning_gretl_into.tex`: overview of machine learning methods in Gretl, including supervised and unsupervised examples.

## Gretl Example Scripts

The `code/` directory contains Gretl/Hansl scripts that accompany the lectures. These examples cover, among other topics:

- naive and regression-based forecasting
- time-series cross-validation
- ridge and lasso regression
- K-nearest neighbors classification
- random forests
- k-means clustering

Some scripts also rely on local helper code included in this repository.

## Running the Gretl Examples

Before running an example script, students should read the script carefully. Several examples assume that required Gretl add-on packages have already been installed locally, and some examples also rely on external Gretl dataset collections.

In particular, some scripts refer to add-on packages such as `regls`, `PandasPort`, `fdensity`, `knn`, `heatmap`, `basis_functions`, `random_forest`, and `CvDataSplitter`. In addition, some examples use datasets such as `Hitters.gdt` or `keane.gdt`, which may need to be installed locally as part of Gretl dataset collections.

For most examples, the local working directory also needs to be set correctly. Several scripts use relative paths and therefore assume that the repository root, or another suitable local project folder, has been defined as the Gretl workdir before execution.

For plotting and data access, it is recommended to create and maintain dedicated `data/` and `figures/` subfolders in the working directory.

Some examples have additional external requirements. For instance, the random-forest example also depends on a local R installation and the corresponding `randomForest` package.

## Dataset Notes

The repository already contains local data used in the examples, including `data/aus_production.gdt`. At the same time, not all scripts are fully self-contained: some examples expect datasets that are distributed separately through Gretl packages or dataset collections.

## Recommended Folder Structure

The following structure is recommended for local work with the examples:

```text
ancona_erasmus_lectures/
├── code/
├── data/
├── figures/
└── slides/
```

This layout keeps scripts, input data, output figures, and lecture slides clearly separated and matches the assumptions used in most of the example files.

## Intended Use

This repository is primarily meant for students attending the Ancona lectures in April 2026. It can be used to review the lecture content, inspect the Gretl scripts discussed in class, and reproduce selected examples in a local Gretl installation.
