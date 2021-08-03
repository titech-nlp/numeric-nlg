Data used in [Towards Table-to-Text Generation with Numerical Reasoning](https://aclanthology.org/2021.acl-long.115/ "Towards Table-to-Text Generation with Numerical Reasoning")  (Suadaa et al; ACL-IJCNLP 2021). If you use this data, please cite the above paper.
<br />
<br />
<b>License</b>
<br />
Distributed under the [Creative Commons 4.0 Attribution-ShareAlike (CC4.0-BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/).
<br />
<br />
<br />

<b>Table (json)</b>
```
[
    ...
    {
        "table_id_paper": "D16-1132table_3",
        "caption": "Results of instance-wise evaluation for anaphoric and cataphoric sets",
        "row_header_level": 4,
        "row_headers": [
            [
                "Set",
                "Anaphoric",
                "Method",
                "single-column CNN (w/ position vec.)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE+SURFSEQ)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE+DEPTREE)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE+SURFSEQ+DEPTREE)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE+SURFSEQ+PREDCONTEXT)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (BASE+DEPTREE+PREDCONTEXT)"
            ],
            [
                "Set",
                "Anaphoric",
                "Method",
                "MCNN (Proposed)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "single-column CNN (w/ position vec.)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE+SURFSEQ)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE+DEPTREE)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE+SURFSEQ+DEPTREE)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE+SURFSEQ+PREDCONTEXT)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (BASE+DEPTREE+PREDCONTEXT)"
            ],
            [
                "Set",
                "Cataphoric",
                "Method",
                "MCNN (Proposed)"
            ]
        ],
        "column_header_level": 1,
        "column_headers": [
            [
                "Recall"
            ],
            [
                "Precision"
            ],
            [
                "F-score"
            ],
            [
                "Avg.P"
            ]
        ],
        "contents": [
            [
                "0.445",
                "0.525",
                "0.481",
                "0.341"
            ],
            [
                "0.591",
                "0.33",
                "0.424",
                "0.367"
            ],
            [
                "0.555",
                "0.566",
                "0.56",
                "0.565"
            ],
            [
                "0.389",
                "0.615",
                "0.476",
                "0.518"
            ],
            [
                "0.503",
                "0.66",
                "0.571",
                "0.599"
            ],
            [
                "0.535",
                "0.611",
                "0.57",
                "0.581"
            ],
            [
                "0.33",
                "0.699",
                "0.449",
                "0.528"
            ],
            [
                "0.492",
                "0.673",
                "0.569",
                "0.602"
            ],
            [
                "0.163",
                "0.293",
                "0.209",
                "0.163"
            ],
            [
                "0.171",
                "0.13",
                "0.148",
                "0.099"
            ],
            [
                "0.202",
                "0.417",
                "0.272",
                "0.257"
            ],
            [
                "0.268",
                "0.438",
                "0.332",
                "0.329"
            ],
            [
                "0.195",
                "0.525",
                "0.285",
                "0.33"
            ],
            [
                "0.258",
                "0.406",
                "0.316",
                "0.276"
            ],
            [
                "0.24",
                "0.488",
                "0.322",
                "0.341"
            ],
            [
                "0.251",
                "0.522",
                "0.339",
                "0.337"
            ]
        ],
        "metrics_loc": "column",
        "metrics_type": [
            "Recall",
            "Precision",
            "F-score",
            "Avg.P"
        ],
        "target_entity": [
            "MCNN (Proposed)"
        ],
        "table_html_clean": "<table border='1' class='dataframe'>  <thead>    <tr style='text-align: right;'>      <th></th>      <th>Recall</th>      <th>Precision</th>      <th>F-score</th>      <th>Avg.P</th>    </tr>  </thead>  <tbody>    <tr>      <td>Set || Anaphoric || Method || single-column CNN (w/ position vec.)</td>      <td>0.445</td>      <td>0.525</td>      <td>0.481</td>      <td>0.341</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE)</td>      <td>0.591</td>      <td>0.33</td>      <td>0.424</td>      <td>0.367</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE+SURFSEQ)</td>      <td>0.555</td>      <td>0.566</td>      <td>0.56</td>      <td>0.565</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE+DEPTREE)</td>      <td>0.389</td>      <td>0.615</td>      <td>0.476</td>      <td>0.518</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE+SURFSEQ+DEPTREE)</td>      <td>0.503</td>      <td>0.66</td>      <td>0.571</td>      <td>0.599</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE+SURFSEQ+PREDCONTEXT)</td>      <td>0.535</td>      <td>0.611</td>      <td>0.57</td>      <td>0.581</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (BASE+DEPTREE+PREDCONTEXT)</td>      <td>0.33</td>      <td>0.699</td>      <td>0.449</td>      <td>0.528</td>    </tr>    <tr>      <td>Set || Anaphoric || Method || MCNN (Proposed)</td>      <td>0.492</td>      <td>0.673</td>      <td>0.569</td>      <td>0.602</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || single-column CNN (w/ position vec.)</td>      <td>0.163</td>      <td>0.293</td>      <td>0.209</td>      <td>0.163</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE)</td>      <td>0.171</td>      <td>0.13</td>      <td>0.148</td>      <td>0.099</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE+SURFSEQ)</td>      <td>0.202</td>      <td>0.417</td>      <td>0.272</td>      <td>0.257</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE+DEPTREE)</td>      <td>0.268</td>      <td>0.438</td>      <td>0.332</td>      <td>0.329</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE+SURFSEQ+DEPTREE)</td>      <td>0.195</td>      <td>0.525</td>      <td>0.285</td>      <td>0.33</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE+SURFSEQ+PREDCONTEXT)</td>      <td>0.258</td>      <td>0.406</td>      <td>0.316</td>      <td>0.276</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (BASE+DEPTREE+PREDCONTEXT)</td>      <td>0.24</td>      <td>0.488</td>      <td>0.322</td>      <td>0.341</td>    </tr>    <tr>      <td>Set || Cataphoric || Method || MCNN (Proposed)</td>      <td>0.251</td>      <td>0.522</td>      <td>0.339</td>      <td>0.337</td>    </tr>  </tbody></table>",
        "table_name": "Table 3",
        "table_id": "table_3",
        "paper_id": "D16-1132",
        "page_no": 9,
        "dir": "emnlp2016",
        "valid": 1
    },
    ...
]
```
<br />
<br />
<b>Table Desc (json)</b>
<br />
<br />


```
[
    ...
    {
        "table_id_paper": "D16-1132table_3",
        "description": "The results in Table 3 show that our MCNN-based method achieved better average precision than the single-column CNN baseline except the method that uses only the BASE column set for the cataphoric case. The results also demonstrate that each column set consistently contributes to improving the average precision for both the anaphoric and cataphoric cases. However, Table 3 shows that the average precision for the cataphoric set remains low. As one future direction for further improvement, we need to explore clues for identifying cataphoric relations more accurately.",
        "sentences": [
            "The results in Table 3 show that our MCNN-based method achieved better average precision than the single-column CNN baseline except the method that uses only the BASE column set for the cataphoric case.",
            "The results also demonstrate that each column set consistently contributes to improving the average precision for both the anaphoric and cataphoric cases.",
            "However, Table 3 shows that the average precision for the cataphoric set remains low.",
            "As one future direction for further improvement, we need to explore clues for identifying cataphoric relations more accurately."
        ],
        "class_sentence": [
            1,
            1,
            1,
            0
        ],
        "header_mention": [
            [
                "MCNN (Proposed)",
                "single-column CNN (w/ position vec.)",
                "MCNN (BASE)",
                "Avg.P"
            ],
            [
                "Avg.P",
                "Anaphoric",
                "Cataphoric"
            ],
            [
                "Cataphoric",
                "Avg.P"
            ],
            null
        ],
        "n_sentence": 4.0,
        "table_id": "table_3",
        "paper_id": "D16-1132",
        "valid": 1
    },
    ...
]
```

