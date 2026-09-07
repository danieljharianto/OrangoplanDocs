#Table
Table Tools handle tabular and geospatial file data within the modeling environment. The tools are divided into three categories: File I/O, for importing and exporting CSV, XLS, and GeoJSON data; Data Preview and Manipulation, for inspecting, cleaning, and transforming datasets; and Data Classification, for organizing numeric data into meaningful groups.


### File I/O



<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- CSV Import -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Import_CSV.png" alt="CSV Import" style="height:25px; margin-bottom:5px;">
          <span>CSV Import</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Import CSV File</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">File</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">File Path</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Path to the CSV file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers as a list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
    </tr>

    <!-- CSV Export -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Export_CSV.png" alt="CSV Export" style="height:25px; margin-bottom:5px;">
          <span>CSV Export</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export as CSV File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File path to export</td>
    </tr>

    <!-- XLS Import -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Import_XLS.png" alt="XLS Import" style="height:25px; margin-bottom:5px;">
          <span>XLS Import</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Import XLS File</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">File</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">File Path</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Path to the CSV file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers as a list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
    </tr>

    <!-- XLS Export -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Export_XLS.png" alt="XLS Export" style="height:25px; margin-bottom:5px;">
          <span>XLS Export</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export as XLS File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Export status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File path to export</td>
    </tr>

    <!-- GEOJSON Import -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Import_GeoJSON.png" alt="GEOJSON Import" style="height:25px; margin-bottom:5px;">
          <span>GEOJSON Import</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Import GeoJSON files and convert to Rhino geometry</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">File</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">Path to the GeoJSON file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Crv</td>
      <td style="padding:12px; border:1px solid #ddd;">Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">LineStrings and MultiLineStrings</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Scale</td>
      <td style="padding:12px; border:1px solid #ddd;">Scale</td>
      <td style="padding:12px; border:1px solid #ddd;">Scale multiplier</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pts</td>
      <td style="padding:12px; border:1px solid #ddd;">Points</td>
      <td style="padding:12px; border:1px solid #ddd;">Points and MultiPoints</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">EPSG</td>
      <td style="padding:12px; border:1px solid #ddd;">EPSG Code</td>
      <td style="padding:12px; border:1px solid #ddd;">Input EPSG code (default 4326 = WGS84), auto-detected from the file's CRS when present</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Poly</td>
      <td style="padding:12px; border:1px solid #ddd;">Polygons</td>
      <td style="padding:12px; border:1px solid #ddd;">Polygons as Breps</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Prop</td>
      <td style="padding:12px; border:1px solid #ddd;">Properties</td>
      <td style="padding:12px; border:1px solid #ddd;">Feature properties as JSON</td>
    </tr>

    <!-- GEOJSON Export -->
    <tr>
      <td rowspan="6" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Export_GeoJSON.png" alt="GEOJSON Export" style="height:25px; margin-bottom:5px;">
          <span>GEOJSON Export</span>
        </div>
      </td>
      <td rowspan="6" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Convert Rhino geometry and export as a GeoJSON file</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pts</td>
      <td style="padding:12px; border:1px solid #ddd;">Points</td>
      <td style="padding:12px; border:1px solid #ddd;">Points to export as Point features</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">GJ</td>
      <td style="padding:12px; border:1px solid #ddd;">GeoJSON String</td>
      <td style="padding:12px; border:1px solid #ddd;">Exported GeoJSON as string</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Crv</td>
      <td style="padding:12px; border:1px solid #ddd;">Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Curves to export as LineString features</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Path</td>
      <td style="padding:12px; border:1px solid #ddd;">File Path</td>
      <td style="padding:12px; border:1px solid #ddd;">Path to exported file</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Poly</td>
      <td style="padding:12px; border:1px solid #ddd;">Polygons</td>
      <td style="padding:12px; border:1px solid #ddd;">Polygons to export as Polygon features</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Count</td>
      <td style="padding:12px; border:1px solid #ddd;">Feature Count</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of features exported</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">File</td>
      <td style="padding:12px; border:1px solid #ddd;">Output File</td>
      <td style="padding:12px; border:1px solid #ddd;">Full path to output GeoJSON file</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">EPSG</td>
      <td style="padding:12px; border:1px solid #ddd;">CRS/EPSG</td>
      <td style="padding:12px; border:1px solid #ddd;">EPSG code (e.g., 4326 for WGS84, 3857 for Web Mercator)</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Props</td>
      <td style="padding:12px; border:1px solid #ddd;">Properties</td>
      <td style="padding:12px; border:1px solid #ddd;">JSON properties for each feature (optional, one per feature)</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>

    
### Data Preview & Manipulation

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Table Preview -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Table_Preview.png" alt="Table Preview" style="height:25px; margin-bottom:5px;">
          <span>Table Preview</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Preview CSV or XLS File</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Column headers for CSV</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Prev</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Formatted Preview</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Formatted CSV preview with padding</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data to export as a tree</td>
    </tr>

    <!-- Column Add -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Add Column.png" alt="Column Add" style="height:25px; margin-bottom:5px;">
          <span>Column Add</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Add new column in data tree</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bh</td>
      <td style="padding:12px; border:1px solid #ddd;">Base Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers of the base CSV</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Uh</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Combined headers of the updated CSV</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bd</td>
      <td style="padding:12px; border:1px solid #ddd;">Base Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data tree of the base CSV</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ud</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated CSV data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Nh</td>
      <td style="padding:12px; border:1px solid #ddd;">New Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers of the new columns</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Nd</td>
      <td style="padding:12px; border:1px solid #ddd;">New Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data tree of the new columns</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Column Remove -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Remove Column.png" alt="Column Remove" style="height:25px; margin-bottom:5px;">
          <span>Column Remove</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Remove column in data tree</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">List of CSV headers</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Uh</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Headers</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated headers</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">CSV data organized as a tree (columns as branches)</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ud</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Updated CSV data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Rh</td>
      <td style="padding:12px; border:1px solid #ddd;">Header to Remove</td>
      <td style="padding:12px; border:1px solid #ddd;">Header of the column to remove</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Pivot by Header -->
    <tr>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Pivot_by_Header.png" alt="Pivot by Header" style="height:25px; margin-bottom:5px;">
          <span>Pivot by Header</span>
        </div>
      </td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Pivot data by a specific column header</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Data</td>
      <td style="padding:12px; border:1px solid #ddd;">Data Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Data as tree</td>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Group</td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Grouped Data</td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Grouped data as a tree</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Group Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Name of the header to use for grouping key</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Value Column</td>
      <td style="padding:12px; border:1px solid #ddd;">Name of the header to extract values from</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Head</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove Header</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove header values in each group</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Dups</td>
      <td style="padding:12px; border:1px solid #ddd;">Dremove Duplicates</td>
      <td style="padding:12px; border:1px solid #ddd;">Remove duplicate values in each group</td>
    </tr>
  </tbody>
</table>

### Data Classification

<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #e8e8e8;">
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Tool</th>
      <th rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Function</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Input</th>
      <th colspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; background-color: #e8e8e8;">Output</th>
    </tr>
    <tr style="background-color: #e8e8e8;">
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Interval Classifier -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Interval Classifier.png" alt="Interval Classifier" style="height:25px; margin-bottom:5px;">
          <span>Interval Classifier</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Divides numeric data into equal-width interval</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">N</td>
      <td style="padding:12px; border:1px solid #ddd;">Numbers</td>
      <td style="padding:12px; border:1px solid #ddd;">List of values to classify</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Max</td>
      <td style="padding:12px; border:1px solid #ddd;">Max</td>
      <td style="padding:12px; border:1px solid #ddd;">Maximum value in list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">n</td>
      <td style="padding:12px; border:1px solid #ddd;">Interval Segments</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of interval division</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Min</td>
      <td style="padding:12px; border:1px solid #ddd;">Min</td>
      <td style="padding:12px; border:1px solid #ddd;">Minimum value in list</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">I</td>
      <td style="padding:12px; border:1px solid #ddd;">Intervals</td>
      <td style="padding:12px; border:1px solid #ddd;">List of numeric interval strings</td>
    </tr>
  </tbody>
</table>



!!! Tip  "Important Tips"

    - Ensure all input files follow the required format, structure, and encoding (e.g., consistent delimiters, headers, and data types).
    - Verify coordinate systems, units, and scale before importing to avoid misalignment or incorrect calculations.
    - Clean and validate datasets in advance by removing null values, duplicates, or inconsistent entries.
    - When exporting data, clearly define attribute fields and naming conventions to maintain compatibility with GIS, CAD, or external analysis tools.
    - Use incremental exports during iterative workflows to track changes and simplify troubleshooting.
    - Always cross-check imported and exported data against the source files to confirm accuracy and completeness.
