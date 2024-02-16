---
license: MIT
library_name: sklearn
tags:
- sklearn
- skops
- tabular-classification
model_format: pickle
model_file: skops-d5ji55.pkl
widget:
- structuredData:
    pixel_0_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_0_1:
    - 0.0
    - 0.0
    - 0.0
    pixel_0_2:
    - 0.0
    - 11.0
    - 8.0
    pixel_0_3:
    - 7.0
    - 16.0
    - 15.0
    pixel_0_4:
    - 12.0
    - 8.0
    - 12.0
    pixel_0_5:
    - 0.0
    - 0.0
    - 4.0
    pixel_0_6:
    - 0.0
    - 0.0
    - 0.0
    pixel_0_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_1_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_1_1:
    - 0.0
    - 6.0
    - 5.0
    pixel_1_2:
    - 4.0
    - 16.0
    - 14.0
    pixel_1_3:
    - 16.0
    - 11.0
    - 4.0
    pixel_1_4:
    - 8.0
    - 13.0
    - 11.0
    pixel_1_5:
    - 0.0
    - 9.0
    - 7.0
    pixel_1_6:
    - 0.0
    - 0.0
    - 0.0
    pixel_1_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_2_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_2_1:
    - 0.0
    - 7.0
    - 0.0
    pixel_2_2:
    - 12.0
    - 16.0
    - 0.0
    pixel_2_3:
    - 11.0
    - 0.0
    - 1.0
    pixel_2_4:
    - 0.0
    - 9.0
    - 14.0
    pixel_2_5:
    - 0.0
    - 16.0
    - 3.0
    pixel_2_6:
    - 0.0
    - 0.0
    - 0.0
    pixel_2_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_3_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_3_1:
    - 0.0
    - 2.0
    - 0.0
    pixel_3_2:
    - 15.0
    - 15.0
    - 2.0
    pixel_3_3:
    - 10.0
    - 12.0
    - 15.0
    pixel_3_4:
    - 8.0
    - 16.0
    - 14.0
    pixel_3_5:
    - 6.0
    - 16.0
    - 1.0
    pixel_3_6:
    - 1.0
    - 3.0
    - 0.0
    pixel_3_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_4_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_4_1:
    - 0.0
    - 0.0
    - 0.0
    pixel_4_2:
    - 15.0
    - 5.0
    - 0.0
    pixel_4_3:
    - 16.0
    - 7.0
    - 8.0
    pixel_4_4:
    - 8.0
    - 7.0
    - 13.0
    pixel_4_5:
    - 10.0
    - 16.0
    - 11.0
    pixel_4_6:
    - 8.0
    - 4.0
    - 0.0
    pixel_4_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_5_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_5_1:
    - 0.0
    - 0.0
    - 0.0
    pixel_5_2:
    - 14.0
    - 0.0
    - 0.0
    pixel_5_3:
    - 7.0
    - 0.0
    - 0.0
    pixel_5_4:
    - 0.0
    - 5.0
    - 0.0
    pixel_5_5:
    - 0.0
    - 16.0
    - 13.0
    pixel_5_6:
    - 12.0
    - 5.0
    - 5.0
    pixel_5_7:
    - 0.0
    - 0.0
    - 0.0
    pixel_6_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_6_1:
    - 0.0
    - 0.0
    - 0.0
    pixel_6_2:
    - 8.0
    - 3.0
    - 12.0
    pixel_6_3:
    - 11.0
    - 7.0
    - 2.0
    pixel_6_4:
    - 0.0
    - 16.0
    - 3.0
    pixel_6_5:
    - 5.0
    - 11.0
    - 12.0
    pixel_6_6:
    - 16.0
    - 0.0
    - 7.0
    pixel_6_7:
    - 2.0
    - 0.0
    - 0.0
    pixel_7_0:
    - 0.0
    - 0.0
    - 0.0
    pixel_7_1:
    - 0.0
    - 0.0
    - 0.0
    pixel_7_2:
    - 0.0
    - 13.0
    - 13.0
    pixel_7_3:
    - 9.0
    - 16.0
    - 16.0
    pixel_7_4:
    - 14.0
    - 11.0
    - 15.0
    pixel_7_5:
    - 14.0
    - 1.0
    - 8.0
    pixel_7_6:
    - 5.0
    - 0.0
    - 0.0
    pixel_7_7:
    - 0.0
    - 0.0
    - 0.0
---

# Model description


    Modell for produksjon av grunnlagsdata for statistikk på diagnoser for uføretrygdede. 
    Modellene benytter numeriske features fra TF-idf vektorisering av fritekstfelter i medisinske dokumenter. 
    
    
    *Utfall*: Predikert *diagnosegruppe-kode* gitt tekstinnhold i grunnlagsdokumenter.

    *Type*: Klassifisering, Logistisk regresjon

    *Læringsmetode*: Veiledet læring

    *Inngår personopplysninger?*: JA

    

## Intended uses & limitations



*Hvilke kjente begrensninger har modellen?*:
  Modellen viser særlige svakheter overfor *ICD-gruppe T* (Skader ol.) 

*Kjente risikoer ved å ta i bruk denne modellen?*:
  Trent på diagnosekodeverk som skal erstattes.  

*Hvilke anbefalinger har du når modellen tas i bruk?*:
 

 - Må retrenes  
 - Datakvalitet må sjekkes bedre
- Kode må optimaliseres 


## Training Procedure


Medisinske dokumenter for alle nye uføretrygdede i perioden 2013-2016. 
Dokumentene er skrevet av tredjeparter (f.eks. leger) og samlet inn gjennom sykemeldings- og AAP-løp.

*Primærkilde(r)*: JOARK


### Hyperparameters

<details>
<summary> Click to expand </summary>

| Hyperparameter               | Value                                                                                                                              |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| aggressive_elimination       | False                                                                                                                              |
| cv                           | 5                                                                                                                                  |
| error_score                  | nan                                                                                                                                |
| estimator__C                 | 1.0                                                                                                                                |
| estimator__class_weight      |                                                                                                                                    |
| estimator__dual              | False                                                                                                                              |
| estimator__fit_intercept     | True                                                                                                                               |
| estimator__intercept_scaling | 1                                                                                                                                  |
| estimator__l1_ratio          |                                                                                                                                    |
| estimator__max_iter          | 100                                                                                                                                |
| estimator__multi_class       | auto                                                                                                                               |
| estimator__n_jobs            |                                                                                                                                    |
| estimator__penalty           | l2                                                                                                                                 |
| estimator__random_state      |                                                                                                                                    |
| estimator__solver            | lbfgs                                                                                                                              |
| estimator__tol               | 0.0001                                                                                                                             |
| estimator__verbose           | 0                                                                                                                                  |
| estimator__warm_start        | False                                                                                                                              |
| estimator                    | LogisticRegression()                                                                                                               |
| factor                       | 3                                                                                                                                  |
| max_resources                | auto                                                                                                                               |
| min_resources                | exhaust                                                                                                                            |
| n_jobs                       | -1                                                                                                                                 |
| param_grid                   | {'fit_intercept': [True, False], 'solver': ['newton-cg', 'lbfgs', 'liblinear', 'sag', 'saga'], 'class_weight': [None, 'balanced']} |
| random_state                 | 42                                                                                                                                 |
| refit                        | True                                                                                                                               |
| resource                     | n_samples                                                                                                                          |
| return_train_score           | True                                                                                                                               |
| scoring                      |                                                                                                                                    |
| verbose                      | 0                                                                                                                                  |

</details>

### Model Plot

<style>#sk-container-id-1 {/* Definition of color scheme common for light and dark mode */--sklearn-color-text: black;--sklearn-color-line: gray;/* Definition of color scheme for unfitted estimators */--sklearn-color-unfitted-level-0: #fff5e6;--sklearn-color-unfitted-level-1: #f6e4d2;--sklearn-color-unfitted-level-2: #ffe0b3;--sklearn-color-unfitted-level-3: chocolate;/* Definition of color scheme for fitted estimators */--sklearn-color-fitted-level-0: #f0f8ff;--sklearn-color-fitted-level-1: #d4ebff;--sklearn-color-fitted-level-2: #b3dbfd;--sklearn-color-fitted-level-3: cornflowerblue;/* Specific color for light theme */--sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));--sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));--sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));--sklearn-color-icon: #696969;@media (prefers-color-scheme: dark) {/* Redefinition of color scheme for dark theme */--sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));--sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));--sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));--sklearn-color-icon: #878787;}
}#sk-container-id-1 {color: var(--sklearn-color-text);
}#sk-container-id-1 pre {padding: 0;
}#sk-container-id-1 input.sk-hidden--visually {border: 0;clip: rect(1px 1px 1px 1px);clip: rect(1px, 1px, 1px, 1px);height: 1px;margin: -1px;overflow: hidden;padding: 0;position: absolute;width: 1px;
}#sk-container-id-1 div.sk-dashed-wrapped {border: 1px dashed var(--sklearn-color-line);margin: 0 0.4em 0.5em 0.4em;box-sizing: border-box;padding-bottom: 0.4em;background-color: var(--sklearn-color-background);
}#sk-container-id-1 div.sk-container {/* jupyter's `normalize.less` sets `[hidden] { display: none; }`but bootstrap.min.css set `[hidden] { display: none !important; }`so we also need the `!important` here to be able to override thedefault hidden behavior on the sphinx rendered scikit-learn.org.See: https://github.com/scikit-learn/scikit-learn/issues/21755 */display: inline-block !important;position: relative;
}#sk-container-id-1 div.sk-text-repr-fallback {display: none;
}div.sk-parallel-item,
div.sk-serial,
div.sk-item {/* draw centered vertical line to link estimators */background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));background-size: 2px 100%;background-repeat: no-repeat;background-position: center center;
}/* Parallel-specific style estimator block */#sk-container-id-1 div.sk-parallel-item::after {content: "";width: 100%;border-bottom: 2px solid var(--sklearn-color-text-on-default-background);flex-grow: 1;
}#sk-container-id-1 div.sk-parallel {display: flex;align-items: stretch;justify-content: center;background-color: var(--sklearn-color-background);position: relative;
}#sk-container-id-1 div.sk-parallel-item {display: flex;flex-direction: column;
}#sk-container-id-1 div.sk-parallel-item:first-child::after {align-self: flex-end;width: 50%;
}#sk-container-id-1 div.sk-parallel-item:last-child::after {align-self: flex-start;width: 50%;
}#sk-container-id-1 div.sk-parallel-item:only-child::after {width: 0;
}/* Serial-specific style estimator block */#sk-container-id-1 div.sk-serial {display: flex;flex-direction: column;align-items: center;background-color: var(--sklearn-color-background);padding-right: 1em;padding-left: 1em;
}/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is
clickable and can be expanded/collapsed.
- Pipeline and ColumnTransformer use this feature and define the default style
- Estimators will overwrite some part of the style using the `sk-estimator` class
*//* Pipeline and ColumnTransformer style (default) */#sk-container-id-1 div.sk-toggleable {/* Default theme specific background. It is overwritten whether we have aspecific estimator or a Pipeline/ColumnTransformer */background-color: var(--sklearn-color-background);
}/* Toggleable label */
#sk-container-id-1 label.sk-toggleable__label {cursor: pointer;display: block;width: 100%;margin-bottom: 0;padding: 0.5em;box-sizing: border-box;text-align: center;
}#sk-container-id-1 label.sk-toggleable__label-arrow:before {/* Arrow on the left of the label */content: "▸";float: left;margin-right: 0.25em;color: var(--sklearn-color-icon);
}#sk-container-id-1 label.sk-toggleable__label-arrow:hover:before {color: var(--sklearn-color-text);
}/* Toggleable content - dropdown */#sk-container-id-1 div.sk-toggleable__content {max-height: 0;max-width: 0;overflow: hidden;text-align: left;/* unfitted */background-color: var(--sklearn-color-unfitted-level-0);
}#sk-container-id-1 div.sk-toggleable__content.fitted {/* fitted */background-color: var(--sklearn-color-fitted-level-0);
}#sk-container-id-1 div.sk-toggleable__content pre {margin: 0.2em;border-radius: 0.25em;color: var(--sklearn-color-text);/* unfitted */background-color: var(--sklearn-color-unfitted-level-0);
}#sk-container-id-1 div.sk-toggleable__content.fitted pre {/* unfitted */background-color: var(--sklearn-color-fitted-level-0);
}#sk-container-id-1 input.sk-toggleable__control:checked~div.sk-toggleable__content {/* Expand drop-down */max-height: 200px;max-width: 100%;overflow: auto;
}#sk-container-id-1 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {content: "▾";
}/* Pipeline/ColumnTransformer-specific style */#sk-container-id-1 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {color: var(--sklearn-color-text);background-color: var(--sklearn-color-unfitted-level-2);
}#sk-container-id-1 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {background-color: var(--sklearn-color-fitted-level-2);
}/* Estimator-specific style *//* Colorize estimator box */
#sk-container-id-1 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {/* unfitted */background-color: var(--sklearn-color-unfitted-level-2);
}#sk-container-id-1 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {/* fitted */background-color: var(--sklearn-color-fitted-level-2);
}#sk-container-id-1 div.sk-label label.sk-toggleable__label,
#sk-container-id-1 div.sk-label label {/* The background is the default theme color */color: var(--sklearn-color-text-on-default-background);
}/* On hover, darken the color of the background */
#sk-container-id-1 div.sk-label:hover label.sk-toggleable__label {color: var(--sklearn-color-text);background-color: var(--sklearn-color-unfitted-level-2);
}/* Label box, darken color on hover, fitted */
#sk-container-id-1 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {color: var(--sklearn-color-text);background-color: var(--sklearn-color-fitted-level-2);
}/* Estimator label */#sk-container-id-1 div.sk-label label {font-family: monospace;font-weight: bold;display: inline-block;line-height: 1.2em;
}#sk-container-id-1 div.sk-label-container {text-align: center;
}/* Estimator-specific */
#sk-container-id-1 div.sk-estimator {font-family: monospace;border: 1px dotted var(--sklearn-color-border-box);border-radius: 0.25em;box-sizing: border-box;margin-bottom: 0.5em;/* unfitted */background-color: var(--sklearn-color-unfitted-level-0);
}#sk-container-id-1 div.sk-estimator.fitted {/* fitted */background-color: var(--sklearn-color-fitted-level-0);
}/* on hover */
#sk-container-id-1 div.sk-estimator:hover {/* unfitted */background-color: var(--sklearn-color-unfitted-level-2);
}#sk-container-id-1 div.sk-estimator.fitted:hover {/* fitted */background-color: var(--sklearn-color-fitted-level-2);
}/* Specification for estimator info (e.g. "i" and "?") *//* Common style for "i" and "?" */.sk-estimator-doc-link,
a:link.sk-estimator-doc-link,
a:visited.sk-estimator-doc-link {float: right;font-size: smaller;line-height: 1em;font-family: monospace;background-color: var(--sklearn-color-background);border-radius: 1em;height: 1em;width: 1em;text-decoration: none !important;margin-left: 1ex;/* unfitted */border: var(--sklearn-color-unfitted-level-1) 1pt solid;color: var(--sklearn-color-unfitted-level-1);
}.sk-estimator-doc-link.fitted,
a:link.sk-estimator-doc-link.fitted,
a:visited.sk-estimator-doc-link.fitted {/* fitted */border: var(--sklearn-color-fitted-level-1) 1pt solid;color: var(--sklearn-color-fitted-level-1);
}/* On hover */
div.sk-estimator:hover .sk-estimator-doc-link:hover,
.sk-estimator-doc-link:hover,
div.sk-label-container:hover .sk-estimator-doc-link:hover,
.sk-estimator-doc-link:hover {/* unfitted */background-color: var(--sklearn-color-unfitted-level-3);color: var(--sklearn-color-background);text-decoration: none;
}div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,
.sk-estimator-doc-link.fitted:hover,
div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,
.sk-estimator-doc-link.fitted:hover {/* fitted */background-color: var(--sklearn-color-fitted-level-3);color: var(--sklearn-color-background);text-decoration: none;
}/* Span, style for the box shown on hovering the info icon */
.sk-estimator-doc-link span {display: none;z-index: 9999;position: relative;font-weight: normal;right: .2ex;padding: .5ex;margin: .5ex;width: min-content;min-width: 20ex;max-width: 50ex;color: var(--sklearn-color-text);box-shadow: 2pt 2pt 4pt #999;/* unfitted */background: var(--sklearn-color-unfitted-level-0);border: .5pt solid var(--sklearn-color-unfitted-level-3);
}.sk-estimator-doc-link.fitted span {/* fitted */background: var(--sklearn-color-fitted-level-0);border: var(--sklearn-color-fitted-level-3);
}.sk-estimator-doc-link:hover span {display: block;
}/* "?"-specific style due to the `<a>` HTML tag */#sk-container-id-1 a.estimator_doc_link {float: right;font-size: 1rem;line-height: 1em;font-family: monospace;background-color: var(--sklearn-color-background);border-radius: 1rem;height: 1rem;width: 1rem;text-decoration: none;/* unfitted */color: var(--sklearn-color-unfitted-level-1);border: var(--sklearn-color-unfitted-level-1) 1pt solid;
}#sk-container-id-1 a.estimator_doc_link.fitted {/* fitted */border: var(--sklearn-color-fitted-level-1) 1pt solid;color: var(--sklearn-color-fitted-level-1);
}/* On hover */
#sk-container-id-1 a.estimator_doc_link:hover {/* unfitted */background-color: var(--sklearn-color-unfitted-level-3);color: var(--sklearn-color-background);text-decoration: none;
}#sk-container-id-1 a.estimator_doc_link.fitted:hover {/* fitted */background-color: var(--sklearn-color-fitted-level-3);
}
</style><div id="sk-container-id-1" class="sk-top-container" style="overflow: auto;"><div class="sk-text-repr-fallback"><pre>HalvingGridSearchCV(estimator=LogisticRegression(), n_jobs=-1,param_grid={&#x27;class_weight&#x27;: [None, &#x27;balanced&#x27;],&#x27;fit_intercept&#x27;: [True, False],&#x27;solver&#x27;: [&#x27;newton-cg&#x27;, &#x27;lbfgs&#x27;, &#x27;liblinear&#x27;,&#x27;sag&#x27;, &#x27;saga&#x27;]},random_state=42)</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class="sk-container" hidden><div class="sk-item sk-dashed-wrapped"><div class="sk-label-container"><div class="sk-label fitted sk-toggleable"><input class="sk-toggleable__control sk-hidden--visually" id="sk-estimator-id-1" type="checkbox" ><label for="sk-estimator-id-1" class="sk-toggleable__label fitted sk-toggleable__label-arrow fitted">&nbsp;&nbsp;HalvingGridSearchCV<a class="sk-estimator-doc-link fitted" rel="noreferrer" target="_blank" href="https://scikit-learn.org/1.4/modules/generated/sklearn.model_selection.HalvingGridSearchCV.html">?<span>Documentation for HalvingGridSearchCV</span></a><span class="sk-estimator-doc-link fitted">i<span>Fitted</span></span></label><div class="sk-toggleable__content fitted"><pre>HalvingGridSearchCV(estimator=LogisticRegression(), n_jobs=-1,param_grid={&#x27;class_weight&#x27;: [None, &#x27;balanced&#x27;],&#x27;fit_intercept&#x27;: [True, False],&#x27;solver&#x27;: [&#x27;newton-cg&#x27;, &#x27;lbfgs&#x27;, &#x27;liblinear&#x27;,&#x27;sag&#x27;, &#x27;saga&#x27;]},random_state=42)</pre></div> </div></div><div class="sk-parallel"><div class="sk-parallel-item"><div class="sk-item"><div class="sk-label-container"><div class="sk-label fitted sk-toggleable"><input class="sk-toggleable__control sk-hidden--visually" id="sk-estimator-id-2" type="checkbox" ><label for="sk-estimator-id-2" class="sk-toggleable__label fitted sk-toggleable__label-arrow fitted">estimator: LogisticRegression</label><div class="sk-toggleable__content fitted"><pre>LogisticRegression()</pre></div> </div></div><div class="sk-serial"><div class="sk-item"><div class="sk-estimator fitted sk-toggleable"><input class="sk-toggleable__control sk-hidden--visually" id="sk-estimator-id-3" type="checkbox" ><label for="sk-estimator-id-3" class="sk-toggleable__label fitted sk-toggleable__label-arrow fitted">&nbsp;LogisticRegression<a class="sk-estimator-doc-link fitted" rel="noreferrer" target="_blank" href="https://scikit-learn.org/1.4/modules/generated/sklearn.linear_model.LogisticRegression.html">?<span>Documentation for LogisticRegression</span></a></label><div class="sk-toggleable__content fitted"><pre>LogisticRegression()</pre></div> </div></div></div></div></div></div></div></div></div>

## Evaluation Results

| Metric   |    Value |
|----------|----------|
| accuracy | 0.968519 |
| f1 score | 0.968113 |

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

### Model description/Evaluation Results/Hyperparameter search results

<details>
<summary> Click to expand </summary>

|   iter |   n_resources |   mean_fit_time |   std_fit_time |   mean_score_time |   std_score_time | param_class_weight   | param_fit_intercept   | param_solver   | params                                                                      |   split0_test_score |   split1_test_score |   split2_test_score |   split3_test_score |   split4_test_score |   mean_test_score |   std_test_score |   rank_test_score |   split0_train_score |   split1_train_score |   split2_train_score |   split3_train_score |   split4_train_score |   mean_train_score |   std_train_score |
|--------|---------------|-----------------|----------------|-------------------|------------------|----------------------|-----------------------|----------------|-----------------------------------------------------------------------------|---------------------|---------------------|---------------------|---------------------|---------------------|-------------------|------------------|-------------------|----------------------|----------------------|----------------------|----------------------|----------------------|--------------------|-------------------|
|      0 |           139 |      0.0221236  |    0.00725089  |        0.00222535 |      0.000716791 |                      | True                  | newton-cg      | {'class_weight': None, 'fit_intercept': True, 'solver': 'newton-cg'}        |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.962963 |          0.911111 |       0.0645763  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0179595  |    0.0014954   |        0.00144377 |      7.32082e-05 |                      | True                  | lbfgs          | {'class_weight': None, 'fit_intercept': True, 'solver': 'lbfgs'}            |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0126202  |    0.000536567 |        0.00132298 |      0.000142849 |                      | True                  | liblinear      | {'class_weight': None, 'fit_intercept': True, 'solver': 'liblinear'}        |            0.851852 |            0.888889 |            0.962963 |            0.925926 |            0.962963 |          0.918519 |       0.0431922  |                13 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0299973  |    0.00300128  |        0.00199833 |      0.000894054 |                      | True                  | sag            | {'class_weight': None, 'fit_intercept': True, 'solver': 'sag'}              |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0249837  |    0.000851766 |        0.00146275 |      0.000183737 |                      | True                  | saga           | {'class_weight': None, 'fit_intercept': True, 'solver': 'saga'}             |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0091537  |    0.000869527 |        0.00155072 |      0.000526431 |                      | False                 | newton-cg      | {'class_weight': None, 'fit_intercept': False, 'solver': 'newton-cg'}       |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0108895  |    0.00143377  |        0.00165591 |      0.000718981 |                      | False                 | lbfgs          | {'class_weight': None, 'fit_intercept': False, 'solver': 'lbfgs'}           |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0120644  |    0.000470584 |        0.0014997  |      0.000245231 |                      | False                 | liblinear      | {'class_weight': None, 'fit_intercept': False, 'solver': 'liblinear'}       |            0.851852 |            0.888889 |            0.962963 |            0.925926 |            0.962963 |          0.918519 |       0.0431922  |                13 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0212104  |    0.001229    |        0.00134788 |      0.000186239 |                      | False                 | sag            | {'class_weight': None, 'fit_intercept': False, 'solver': 'sag'}             |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.962963 |          0.911111 |       0.0645763  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0255075  |    0.000882748 |        0.00129018 |      1.50424e-05 |                      | False                 | saga           | {'class_weight': None, 'fit_intercept': False, 'solver': 'saga'}            |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.925926 |          0.903704 |       0.0601781  |                24 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0133646  |    0.00338122  |        0.00143509 |      0.000333082 | balanced             | True                  | newton-cg      | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'newton-cg'}  |            0.814815 |            0.888889 |            1        |            0.925926 |            0.925926 |          0.911111 |       0.0601781  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0114851  |    0.00114202  |        0.00131302 |      0.000105549 | balanced             | True                  | lbfgs          | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'lbfgs'}      |            0.814815 |            0.888889 |            1        |            0.925926 |            0.925926 |          0.911111 |       0.0601781  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0123368  |    0.000563534 |        0.00117712 |      9.21423e-05 | balanced             | True                  | liblinear      | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'liblinear'}  |            0.851852 |            0.925926 |            0.962963 |            0.925926 |            0.962963 |          0.925926 |       0.040572   |                11 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0241077  |    0.00457688  |        0.00120897 |      5.37246e-05 | balanced             | True                  | sag            | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'sag'}        |            0.814815 |            0.777778 |            1        |            0.962963 |            0.925926 |          0.896296 |       0.0857469  |                30 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0273297  |    0.00703691  |        0.00155878 |      0.000547314 | balanced             | True                  | saga           | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'saga'}       |            0.814815 |            0.888889 |            1        |            0.962963 |            0.925926 |          0.918519 |       0.0637209  |                13 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.00950909 |    0.000376932 |        0.00117621 |      9.503e-05   | balanced             | False                 | newton-cg      | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'newton-cg'} |            0.814815 |            0.888889 |            1        |            0.925926 |            0.925926 |          0.911111 |       0.0601781  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0125923  |    0.00405783  |        0.00117416 |      5.51285e-05 | balanced             | False                 | lbfgs          | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'lbfgs'}     |            0.814815 |            0.888889 |            1        |            0.925926 |            0.925926 |          0.911111 |       0.0601781  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0130692  |    0.00149098  |        0.00129795 |      0.000101508 | balanced             | False                 | liblinear      | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'liblinear'} |            0.851852 |            0.925926 |            0.962963 |            0.925926 |            0.962963 |          0.925926 |       0.040572   |                11 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0233613  |    0.00414742  |        0.00146184 |      0.000259545 | balanced             | False                 | sag            | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'sag'}       |            0.814815 |            0.851852 |            0.962963 |            0.962963 |            0.962963 |          0.911111 |       0.0645763  |                17 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      0 |           139 |      0.0242352  |    0.00219396  |        0.00135851 |      0.000146632 | balanced             | False                 | saga           | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'saga'}      |            0.814815 |            0.888889 |            1        |            0.962963 |            0.925926 |          0.918519 |       0.0637209  |                13 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0195125  |    0.00392281  |        0.00118814 |      9.08778e-05 | balanced             | True                  | newton-cg      | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'newton-cg'}  |            0.939759 |            0.963855 |            0.915663 |            0.951807 |            0.915663 |          0.937349 |       0.0192771  |                 6 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0751036  |    0.00855066  |        0.00181813 |      0.00116587  | balanced             | True                  | saga           | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'saga'}       |            0.951807 |            0.951807 |            0.939759 |            0.951807 |            0.915663 |          0.942169 |       0.0140505  |                 4 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0265983  |    0.00439299  |        0.00124273 |      8.05935e-05 |                      | False                 | liblinear      | {'class_weight': None, 'fit_intercept': False, 'solver': 'liblinear'}       |            0.951807 |            0.951807 |            0.915663 |            0.927711 |            0.903614 |          0.93012  |       0.0192771  |                 7 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0310348  |    0.00254025  |        0.00174317 |      0.000759048 |                      | True                  | liblinear      | {'class_weight': None, 'fit_intercept': True, 'solver': 'liblinear'}        |            0.951807 |            0.951807 |            0.915663 |            0.927711 |            0.903614 |          0.93012  |       0.0192771  |                 7 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0737365  |    0.0067582   |        0.00124574 |      3.47781e-05 | balanced             | False                 | saga           | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'saga'}      |            0.939759 |            0.963855 |            0.939759 |            0.951807 |            0.915663 |          0.942169 |       0.0159837  |                 4 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0290708  |    0.0032183   |        0.00127988 |      8.65486e-05 | balanced             | True                  | liblinear      | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'liblinear'}  |            0.951807 |            0.951807 |            0.915663 |            0.927711 |            0.903614 |          0.93012  |       0.0192771  |                 7 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      1 |           417 |      0.0262667  |    0.00319043  |        0.00126047 |      8.46276e-05 | balanced             | False                 | liblinear      | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'liblinear'} |            0.951807 |            0.951807 |            0.915663 |            0.927711 |            0.903614 |          0.93012  |       0.0192771  |                 7 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      2 |          1251 |      0.118899   |    0.0318654   |        0.00130262 |      4.54575e-05 | balanced             | True                  | newton-cg      | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'newton-cg'}  |            0.964    |            0.96     |            0.951807 |            0.955823 |            0.939759 |          0.954278 |       0.00832528 |                 3 |                    1 |                    1 |                    1 |                    1 |             1        |             1      |         0         |
|      2 |          1251 |      0.216266   |    0.0132002   |        0.00145454 |      0.000195536 | balanced             | True                  | saga           | {'class_weight': 'balanced', 'fit_intercept': True, 'solver': 'saga'}       |            0.96     |            0.964    |            0.955823 |            0.963855 |            0.947791 |          0.958294 |       0.00604669 |                 1 |                    1 |                    1 |                    1 |                    1 |             0.999001 |             0.9998 |         0.0003996 |
|      2 |          1251 |      0.213011   |    0.016198    |        0.0013958  |      9.62522e-05 | balanced             | False                 | saga           | {'class_weight': 'balanced', 'fit_intercept': False, 'solver': 'saga'}      |            0.96     |            0.96     |            0.955823 |            0.963855 |            0.943775 |          0.956691 |       0.00693976 |                 2 |                    1 |                    1 |                    1 |                    1 |             0.999001 |             0.9998 |         0.0003996 |

</details>

### Model description/Evaluation Results/Classification report

<details>
<summary> Click to expand </summary>

| index        |   precision |   recall |   f1-score |   support |
|--------------|-------------|----------|------------|-----------|
| Diag0        |    1        | 1        |   1        |        53 |
| Diag1        |    0.958333 | 0.92     |   0.938776 |        50 |
| Diag2        |    0.921569 | 1        |   0.959184 |        47 |
| Diag3        |    0.981132 | 0.962963 |   0.971963 |        54 |
| Diag4        |    1        | 0.983333 |   0.991597 |        60 |
| Diag5        |    0.953846 | 0.939394 |   0.946565 |        66 |
| Diag6        |    0.981132 | 0.981132 |   0.981132 |        53 |
| Diag7        |    1        | 0.981818 |   0.990826 |        55 |
| Diag8        |    0.913043 | 0.976744 |   0.94382  |        43 |
| Diag9        |    0.965517 | 0.949153 |   0.957265 |        59 |
| macro avg    |    0.967457 | 0.969454 |   0.968113 |       540 |
| weighted avg |    0.969244 | 0.968519 |   0.968581 |       540 |

</details>

# How to Get Started with the Model

[More Information Needed]

# Model Card Authors

Team TADA, PO xyz

# Model Card Contact

**Slack**: #tada, **epost**: ta-kontakt-med-oss@nav.no

# Citation

**Etterlevelse**: etterlevelse.intern.nav.no```

# Valg av modell

 
Klassifisering vha `LogisticRegression`. 
Modellen er valgt fordi den representerer en enkel, rask og forklarbar modell for klassifisering av tabulære data.

*Er modellen egenutviklet i Nav eller brukes modell utenifra?*: Egenutviklet  



# Parent model

None

# Evalueringsresultater

Modellen er primært evaluert på test data og optimert for *accuracy* og *F1-score* med 'macro' som gjennomsnittsmetode.
