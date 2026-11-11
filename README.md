# Data Analytics Bootcamp

Each project is maintained as an independent project. Use its own README,
dependency definitions, tests, entry points, and license.

| Project | Original repository |
| --- | --- |
| [python-challenge](projects/python-challenge/) | [GitHub](https://github.com/john-stromberg/python-challenge) |
| [VBA_Homework](projects/VBA_Homework/) | [GitHub](https://github.com/john-stromberg/VBA_Homework) |
| [pandas-challenge](projects/pandas-challenge/) | [GitHub](https://github.com/john-stromberg/pandas-challenge) |
| [matplotlib-challenge](projects/matplotlib-challenge/) | [GitHub](https://github.com/john-stromberg/matplotlib-challenge) |
| [python-api-challenge](projects/python-api-challenge/) | [GitHub](https://github.com/john-stromberg/python-api-challenge) |
| [sql-challenge](projects/sql-challenge/) | [GitHub](https://github.com/john-stromberg/sql-challenge) |
| [sqlalchemy-challenge](projects/sqlalchemy-challenge/) | [GitHub](https://github.com/john-stromberg/sqlalchemy-challenge) |
| [web-scraping-challenge](projects/web-scraping-challenge/) | [GitHub](https://github.com/john-stromberg/web-scraping-challenge) |
| [Web-Design-Challenge](projects/Web-Design-Challenge/) | [GitHub](https://github.com/john-stromberg/Web-Design-Challenge) |
| [javascript-challenge](projects/javascript-challenge/) | [GitHub](https://github.com/john-stromberg/javascript-challenge) |
| [Plot.ly-challenge](projects/Plot.ly-challenge/) | [GitHub](https://github.com/john-stromberg/Plot.ly-challenge) |
| [D3-challenge](projects/D3-challenge/) | [GitHub](https://github.com/john-stromberg/D3-challenge) |
| [leaflet-challenge](projects/leaflet-challenge/) | [GitHub](https://github.com/john-stromberg/leaflet-challenge) |
| [DataProject1](projects/DataProject1/) | [GitHub](https://github.com/john-stromberg/DataProject1) |
| [Crime-Data-ETL-Project](projects/Crime-Data-ETL-Project/) | [GitHub](https://github.com/john-stromberg/Crime-Data-ETL-Project) |
| [Machine-Learning-Investment-Analysis](projects/Machine-Learning-Investment-Analysis/) | [GitHub](https://github.com/john-stromberg/Machine-Learning-Investment-Analysis) |

The source commit and tree for each import are recorded in [IMPORTS.json](IMPORTS.json);
the complete imported commit histories are retained. Run each project from its own
directory. There is no shared installation or unified API.

Project-level GitHub Actions files are preserved as references. GitHub only runs
workflows located under this repository's root `.github/workflows/` directory.

## Large historical data

The current checkout omits the following large datasets. Projects that use
them require restoring the files to the paths shown below:

- `projects/python-challenge/Resources/election_data.csv`:
  [download from the original commit](https://github.com/john-stromberg/python-challenge/blob/56dd1690338623dafcb1ebfd410fee17d40d1da4/Resources/election_data.csv).
- `projects/VBA_Homework/Multiple_year_stock_data.xlsm`:
  [download from the original commit](https://github.com/john-stromberg/VBA_Homework/blob/60bf52fdb7dcb76aa1b7d30f28ac3c9fdb29aded/Multiple_year_stock_data.xlsm).
- `projects/Machine-Learning-Investment-Analysis/Stocks/`: obtain the
  `Stocks` folder from the
  [original commit](https://github.com/john-stromberg/Machine-Learning-Investment-Analysis/tree/240810554e1ced993581c9960b1f9a95762fcafe/Stocks)
  or its
  [source archive](https://github.com/john-stromberg/Machine-Learning-Investment-Analysis/archive/240810554e1ced993581c9960b1f9a95762fcafe.zip).

Jupyter checkpoint files from that project are also omitted. All omitted files
remain in the imported Git history and the original repositories, so this
cleanup reduces the current checkout but does not reduce the full history size.
