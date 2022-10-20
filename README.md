# Code Description

`code/01_sum.R`
- generates summary table
- saves as a `.rds` object in `output/` folder

`code/02_make_plots.R`
- generates plots
- saves as `.png` objects in `output/` folder

`code/04_render_report.R`
- renders `report.Rmd`

`report.Rmd`
- reads summary table generated by `code/01_sum.R`
- reads plots generated by `code/02_make_plots.R`
