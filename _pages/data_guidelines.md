---
title: Data Guidelines
permalink: /data-guide/
layout: splash
---
<h1>Data Guidelines</h1>
<p>
For a complete CEA dataset, we recommend at least 3 of the following data files.
    <ul>
      <li>Table for environmental data</li>
      <li>Table for crop/biological data</li>
      <li>Metadata: description of the dataset</li>
    </ul>
</p>

<div id="data-recommendation">
  <p>
    <h2>Table for environmental data</h2>
    <ul>
      <li>High frequency time-series data</li>
      <li>Logged automatically by sensors/actuators</li>
    </ul>
    <img src="/assets/images/env.png" alt="enviroment data" />
  </p>

  <p>
    <h2>Table for crop/biological data</h2>
    <ul>
      <li>Low frequency time-series data</li>
      <li>Input by humans</li>
    </ul>
    <img src="/assets/images/crop.png" alt="crop data" />
  </p>

  <p>
    <h2>Description file (metadata)</h2>
    <h3>Necessary</h3>

    <ul>
      <li>Brief description of data, including date and location of the crop</li>

      <li>Semantics and unit for each attribute</li>

      <li>Data owner and contact info</li>

      <li>Citation if published</li>
    </ul>
    <h3>Nice to have</h3>

    <ul>
      <li>Funding source</li>

      <li>Specs of instruments and calibration method use, preferably following <a href="https://www.controlledenvironments.org/international-controlled-env-guidelines/">NCERA-101 Guidelines</a></li>

      <li>Known problems limiting the data use</li>

      <li>Names of data sets related to this set</li>

      <li>[anything available and considered useful to other researchers]</li>
    </ul>
  </p>

</div>

<div class="notice--primary">
  <h1>For tabular data, CSV is recommended over Excel</h1>
  <table>
    <thead>
      <tr>
        <th width="50%">CSV</th>
        <th width="50%">XLS</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Text format</td>
        <td>Binary format</td>
      </tr>
      <tr>
        <td>Only 1 table per CSV file</td>
        <td>Can embed multiple tables ("sheets")</td>
      </tr>
      <tr>
        <td>Can track changes</td>
        <td>Can’t track changes</td>
      </tr>
      <tr>
        <td>Can be opened in many programs, including Excel <br /> (hence easier cross-dataset analysis)</td>
        <td>Can only be opened in Excel</td>
      </tr>
      <tr>
        <td>Can be glanced on the browser</td>
        <td></td>
      </tr>
    </tbody>
  </table>
</div>


<h1>Help?</h1>
Please contact Site Manager (Kenneth Tran, x@kentran.net) for assistance.