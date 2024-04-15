# The function `cols_merge()` works correctly

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part 1</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">one</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part 2</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part 3</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">three</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part 4</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part 5</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">five</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"a\">a</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part one</th>\n<td headers=\"stub_1_1 a\" class=\"gt_row gt_right\">1</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part two</th>\n<td headers=\"stub_1_2 a\" class=\"gt_row gt_right\">2</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part three</th>\n<td headers=\"stub_1_3 a\" class=\"gt_row gt_right\">3</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part four</th>\n<td headers=\"stub_1_4 a\" class=\"gt_row gt_right\">4</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part five</th>\n<td headers=\"stub_1_5 a\" class=\"gt_row gt_right\">5</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part i</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">one</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part ii</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part iii</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">three</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part iv</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_left gt_stub\">Part v</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">five</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"mpg\">mpg</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"cyl\">cyl</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"disp\">disp</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"hp\">hp</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"drat\">drat</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"qsec\">qsec</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"vs\">vs</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"am\">am</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"gear\">gear</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"carb\">carb</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><td headers=\"mpg\" class=\"gt_row gt_right\">21.0</td>\n<td headers=\"cyl\" class=\"gt_row gt_right\">6</td>\n<td headers=\"disp\" class=\"gt_row gt_right\">160</td>\n<td headers=\"hp\" class=\"gt_row gt_right\">110</td>\n<td headers=\"drat\" class=\"gt_row gt_right\">3.90</td>\n<td headers=\"qsec\" class=\"gt_row gt_right\">16.46</td>\n<td headers=\"vs\" class=\"gt_row gt_right\">0</td>\n<td headers=\"am\" class=\"gt_row gt_right\">1</td>\n<td headers=\"gear\" class=\"gt_row gt_right\">4</td>\n<td headers=\"carb\" class=\"gt_row gt_right\">4</td></tr>\n    <tr><td headers=\"mpg\" class=\"gt_row gt_right\">21.0</td>\n<td headers=\"cyl\" class=\"gt_row gt_right\">6</td>\n<td headers=\"disp\" class=\"gt_row gt_right\">160</td>\n<td headers=\"hp\" class=\"gt_row gt_right\">110</td>\n<td headers=\"drat\" class=\"gt_row gt_right\">3.90 (2.875)</td>\n<td headers=\"qsec\" class=\"gt_row gt_right\">17.02</td>\n<td headers=\"vs\" class=\"gt_row gt_right\">0</td>\n<td headers=\"am\" class=\"gt_row gt_right\">1</td>\n<td headers=\"gear\" class=\"gt_row gt_right\">4</td>\n<td headers=\"carb\" class=\"gt_row gt_right\">4</td></tr>\n    <tr><td headers=\"mpg\" class=\"gt_row gt_right\">22.8</td>\n<td headers=\"cyl\" class=\"gt_row gt_right\">4</td>\n<td headers=\"disp\" class=\"gt_row gt_right\">108</td>\n<td headers=\"hp\" class=\"gt_row gt_right\">93</td>\n<td headers=\"drat\" class=\"gt_row gt_right\">3.85</td>\n<td headers=\"qsec\" class=\"gt_row gt_right\">18.61</td>\n<td headers=\"vs\" class=\"gt_row gt_right\">1</td>\n<td headers=\"am\" class=\"gt_row gt_right\">1</td>\n<td headers=\"gear\" class=\"gt_row gt_right\">4</td>\n<td headers=\"carb\" class=\"gt_row gt_right\">1</td></tr>\n    <tr><td headers=\"mpg\" class=\"gt_row gt_right\">21.4</td>\n<td headers=\"cyl\" class=\"gt_row gt_right\">6</td>\n<td headers=\"disp\" class=\"gt_row gt_right\">258</td>\n<td headers=\"hp\" class=\"gt_row gt_right\">110</td>\n<td headers=\"drat\" class=\"gt_row gt_right\">3.08 (3.215)</td>\n<td headers=\"qsec\" class=\"gt_row gt_right\">19.44</td>\n<td headers=\"vs\" class=\"gt_row gt_right\">1</td>\n<td headers=\"am\" class=\"gt_row gt_right\">0</td>\n<td headers=\"gear\" class=\"gt_row gt_right\">3</td>\n<td headers=\"carb\" class=\"gt_row gt_right\">1</td></tr>\n    <tr><td headers=\"mpg\" class=\"gt_row gt_right\">18.7</td>\n<td headers=\"cyl\" class=\"gt_row gt_right\">8</td>\n<td headers=\"disp\" class=\"gt_row gt_right\">360</td>\n<td headers=\"hp\" class=\"gt_row gt_right\">175</td>\n<td headers=\"drat\" class=\"gt_row gt_right\">3.15</td>\n<td headers=\"qsec\" class=\"gt_row gt_right\">17.02</td>\n<td headers=\"vs\" class=\"gt_row gt_right\">0</td>\n<td headers=\"am\" class=\"gt_row gt_right\">0</td>\n<td headers=\"gear\" class=\"gt_row gt_right\">3</td>\n<td headers=\"carb\" class=\"gt_row gt_right\">2</td></tr>\n  </tbody>\n  \n  \n</table>"

# The `cols_merge_uncert()` function works correctly

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2.3 ± 0.06</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">A</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">6.3 ± 0.07</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">B</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2.5 ± 0.08</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">C</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2.4 ± 0.09</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">D</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">6.5 ± 0.10</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">E</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"row\">row</th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><td headers=\"row\" class=\"gt_row gt_right\">2.3</td>\n<td headers=\"b\" class=\"gt_row gt_left\">A</td></tr>\n    <tr><td headers=\"row\" class=\"gt_row gt_right\">6.3 ± 0.07</td>\n<td headers=\"b\" class=\"gt_row gt_left\">B</td></tr>\n    <tr><td headers=\"row\" class=\"gt_row gt_right\">2.5</td>\n<td headers=\"b\" class=\"gt_row gt_left\">C</td></tr>\n    <tr><td headers=\"row\" class=\"gt_row gt_right\">2.4 ± 0.09</td>\n<td headers=\"b\" class=\"gt_row gt_left\">D</td></tr>\n    <tr><td headers=\"row\" class=\"gt_row gt_right\">6.5</td>\n<td headers=\"b\" class=\"gt_row gt_left\">E</td></tr>\n  </tbody>\n  \n  \n</table>"

# The `cols_merge_uncert()` fn works nicely with different error bounds

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"value\">value</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">34.5<span style=\"display:inline-block;line-height:1em;text-align:right;font-size:60%;vertical-align:-0.25em;margin-left:0.1em;\">+1.8<br>−2.1</span></td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">29.2</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">36.3</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">31.6<span style=\"display:inline-block;line-height:1em;text-align:right;font-size:60%;vertical-align:-0.25em;margin-left:0.1em;\">+NA<br>−1.8</span></td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">28.5</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">30.9</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">NA</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">NA</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">Inf</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">30.0 ± 0.0</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">32.0<span style=\"display:inline-block;line-height:1em;text-align:right;font-size:60%;vertical-align:-0.25em;margin-left:0.1em;\">+0.0<br>−0.1</span></td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">34.0</td></tr>\n    <tr><td headers=\"value\" class=\"gt_row gt_right\">NaN</td></tr>\n  </tbody>\n  \n  \n</table>"

# The `cols_merge_range()` function works correctly

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">1–6</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">one</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2–7</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">3–8</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">three</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">4–9</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">5–10</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">five</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"a\">a</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">1–one</th>\n<td headers=\"stub_1_1 a\" class=\"gt_row gt_right\">6</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2–two</th>\n<td headers=\"stub_1_2 a\" class=\"gt_row gt_right\">7</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">3–three</th>\n<td headers=\"stub_1_3 a\" class=\"gt_row gt_right\">8</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">4–four</th>\n<td headers=\"stub_1_4 a\" class=\"gt_row gt_right\">9</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">5–five</th>\n<td headers=\"stub_1_5 a\" class=\"gt_row gt_right\">10</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">1–vi</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">one</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2–vii</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">3–viii</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">three</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">4–ix</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">5–x</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">five</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">i–6</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">one</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">ii–7</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">iii–8</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">three</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">iv–9</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">v–10</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">five</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"a\">a</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">1</th>\n<td headers=\"stub_1_1 a\" class=\"gt_row gt_right\">6</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2</th>\n<td headers=\"stub_1_2 a\" class=\"gt_row gt_right\">7–two</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">3</th>\n<td headers=\"stub_1_3 a\" class=\"gt_row gt_right\">8</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">4</th>\n<td headers=\"stub_1_4 a\" class=\"gt_row gt_right\">9–four</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">5</th>\n<td headers=\"stub_1_5 a\" class=\"gt_row gt_right\">10</td></tr>\n  </tbody>\n  \n  \n</table>"

# The `cols_merge_n_pct()` function works correctly

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"\"></th>\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_left\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"b\">b</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><th id=\"stub_1_1\" scope=\"row\" class=\"gt_row gt_right gt_stub\">1 (6.00%)</th>\n<td headers=\"stub_1_1 b\" class=\"gt_row gt_left\">A</td></tr>\n    <tr><th id=\"stub_1_2\" scope=\"row\" class=\"gt_row gt_right gt_stub\">2 (7.00%)</th>\n<td headers=\"stub_1_2 b\" class=\"gt_row gt_left\">B</td></tr>\n    <tr><th id=\"stub_1_3\" scope=\"row\" class=\"gt_row gt_right gt_stub\">3 (8.00%)</th>\n<td headers=\"stub_1_3 b\" class=\"gt_row gt_left\">C</td></tr>\n    <tr><th id=\"stub_1_4\" scope=\"row\" class=\"gt_row gt_right gt_stub\">4 (9.00%)</th>\n<td headers=\"stub_1_4 b\" class=\"gt_row gt_left\">D</td></tr>\n    <tr><th id=\"stub_1_5\" scope=\"row\" class=\"gt_row gt_right gt_stub\">5 (10.00%)</th>\n<td headers=\"stub_1_5 b\" class=\"gt_row gt_left\">E</td></tr>\n  </tbody>\n  \n  \n</table>"

---

    Code
      .
    Output
      [1] "<table class=\"gt_table\" data-quarto-disable-processing=\"false\" data-quarto-bootstrap=\"false\">\n  <thead>\n    <tr class=\"gt_col_headings\">\n      <th class=\"gt_col_heading gt_columns_bottom_border gt_right\" rowspan=\"1\" colspan=\"1\" scope=\"col\" id=\"a\">a</th>\n    </tr>\n  </thead>\n  <tbody class=\"gt_table_body\">\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">1 (7.1%)</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">5</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">0</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">2 (14.3%)</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">NA</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">6</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">5</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">NA</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">0</td></tr>\n    <tr><td headers=\"a\" class=\"gt_row gt_right\">NA</td></tr>\n  </tbody>\n  \n  \n</table>"
