#Design
Design Tools enable designers to test and compare spatial, environmental, and performance criteria directly within parametric models. The tools are divided into three categories: Road Tools, for generating and refining street geometry and sections; Parcel and Building Tools, for shaping parcels, extruding buildings, and managing design attributes; and Viewport Tools, for visualizing density, height, and other spatial performance metrics in real time.

### Road Tools


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
    <!-- Road Offset Tool -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Offset_Road.png" alt="Road Offset Tool" style="height:25px; margin-bottom:5px;">
          <span>Offset Tool</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Offset curve based on categorized width</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Crv</td>
      <td style="padding:12px; border:1px solid #ddd;">Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Input curve to offset</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">U</td>
      <td style="padding:12px; border:1px solid #ddd;">Union Result</td>
      <td style="padding:12px; border:1px solid #ddd;">Union all offset curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Wd</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset widths for each curve</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">O</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset curves</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Wd</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths for each offset curve</td>
    </tr>

    <!-- Road Chamfer Tool -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Road_Chamfer.png" alt="Road Chamfer Tool" style="height:25px; margin-bottom:5px;">
          <span>Chamfer Tool</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Chamfer curve based on relevant offset width</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">U</td>
      <td style="padding:12px; border:1px solid #ddd;">Union Curve</td>
      <td style="padding:12px; border:1px solid #ddd;">Union curve to split</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Chamfer Boundaries</td>
      <td style="padding:12px; border:1px solid #ddd;">Chamfer boundaries</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">O</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset curves for intersection</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">J</td>
      <td style="padding:12px; border:1px solid #ddd;">Join Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Connecting curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Wd</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths for each offset curve</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
      <td style="padding:12px; border:1px solid #ddd;">Chamfered Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Chamfered closed curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
      <td style="padding:12px; border:1px solid #ddd;">Ratio</td>
      <td style="padding:12px; border:1px solid #ddd;">Chamfer circle radius ratio</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Road Fillet Tool -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Road_Fillet.png" alt="Road Fillet Tool" style="height:25px; margin-bottom:5px;">
          <span>Fillet Tool</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Fillet curve based on relevant offset width</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">U</td>
      <td style="padding:12px; border:1px solid #ddd;">Union Curve</td>
      <td style="padding:12px; border:1px solid #ddd;">Union curve to split</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Fillet Boundaries</td>
      <td style="padding:12px; border:1px solid #ddd;">Fillet boundaries</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">O</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Offset curves for intersection</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">J</td>
      <td style="padding:12px; border:1px solid #ddd;">Join Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Connecting curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Wd</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths</td>
      <td style="padding:12px; border:1px solid #ddd;">Widths for each offset curve</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
      <td style="padding:12px; border:1px solid #ddd;">Filleted Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Filleted closed curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
      <td style="padding:12px; border:1px solid #ddd;">Ratio</td>
      <td style="padding:12px; border:1px solid #ddd;">Fillet circle radius ratio</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Road Section -->
    <tr>
      <td rowspan="8" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Road_Section.png" alt="Road Section" style="height:25px; margin-bottom:5px;">
          <span>Road Section</span>
        </div>
      </td>
      <td rowspan="8" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Create road section</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Hc</td>
      <td style="padding:12px; border:1px solid #ddd;">Headway Count</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of headways per side</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Rects</td>
      <td style="padding:12px; border:1px solid #ddd;">Section Rectangles</td>
      <td style="padding:12px; border:1px solid #ddd;">Closed rectangles for each section part</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Hw</td>
      <td style="padding:12px; border:1px solid #ddd;">Headway Width</td>
      <td style="padding:12px; border:1px solid #ddd;">Width of each headway</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Geo</td>
      <td style="padding:12px; border:1px solid #ddd;">Embedded Geometry</td>
      <td style="padding:12px; border:1px solid #ddd;">Embedded car/tree geometry placed on suitable sections</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pc</td>
      <td style="padding:12px; border:1px solid #ddd;">Ped Count</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of pedestrian paths per side</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pw</td>
      <td style="padding:12px; border:1px solid #ddd;">Ped Width</td>
      <td style="padding:12px; border:1px solid #ddd;">Width of each pedestrian path</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Cw</td>
      <td style="padding:12px; border:1px solid #ddd;">Curb Width</td>
      <td style="padding:12px; border:1px solid #ddd;">Width of curbs</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Iw</td>
      <td style="padding:12px; border:1px solid #ddd;">Island Width</td>
      <td style="padding:12px; border:1px solid #ddd;">Width of center island</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">H</td>
      <td style="padding:12px; border:1px solid #ddd;">Lane Height</td>
      <td style="padding:12px; border:1px solid #ddd;">Height of section rectangles</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">T</td>
      <td style="padding:12px; border:1px solid #ddd;">Text Height</td>
      <td style="padding:12px; border:1px solid #ddd;">Height of font</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>



### Parcel & Building Tools

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
    <!-- Recursive Split -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Custom_Recursive_Split.png" alt="Recursive Split" style="height:25px; margin-bottom:5px;">
          <span>Recursive Split</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Splits planar boundaries recursively using subdivided curves</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Curve</td>
      <td style="padding:12px; border:1px solid #ddd;">Base curve boundary</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Sort</td>
      <td style="padding:12px; border:1px solid #ddd;">Sorted</td>
      <td style="padding:12px; border:1px solid #ddd;">Sorted input segments</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">F</td>
      <td style="padding:12px; border:1px solid #ddd;">Fraction</td>
      <td style="padding:12px; border:1px solid #ddd;">Subdivision domain fraction (0.0 to 1.0)</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">S</td>
      <td style="padding:12px; border:1px solid #ddd;">Splits</td>
      <td style="padding:12px; border:1px solid #ddd;">All splitting curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">N</td>
      <td style="padding:12px; border:1px solid #ddd;">Iterations</td>
      <td style="padding:12px; border:1px solid #ddd;">Number of recursive iterations</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">B</td>
      <td style="padding:12px; border:1px solid #ddd;">Boundaries</td>
      <td style="padding:12px; border:1px solid #ddd;">Joined closed curves</td>
    </tr>

    <!-- Extract Parcel -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Extract_Parcel.png" alt="Extract Parcel" style="height:25px; margin-bottom:5px;">
          <span>Extract Parcel</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Extract Parcel by substracting deisgned road and site boundary</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Rd</td>
      <td style="padding:12px; border:1px solid #ddd;">Roads</td>
      <td style="padding:12px; border:1px solid #ddd;">List of closed road curves</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">P</td>
      <td style="padding:12px; border:1px solid #ddd;">Parcels</td>
      <td style="padding:12px; border:1px solid #ddd;">Resulting parcel curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">S</td>
      <td style="padding:12px; border:1px solid #ddd;">Site</td>
      <td style="padding:12px; border:1px solid #ddd;">Site boundary curve</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ct</td>
      <td style="padding:12px; border:1px solid #ddd;">Centroids</td>
      <td style="padding:12px; border:1px solid #ddd;">Center points</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">A</td>
      <td style="padding:12px; border:1px solid #ddd;">Areas</td>
      <td style="padding:12px; border:1px solid #ddd;">Areas of each parcel</td>
    </tr>

    <!-- Calculate Parcel -->
    <tr>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Calculate_Parcel.png" alt="Calculate Parcel" style="height:25px; margin-bottom:5px;">
          <span>Calculate Parcel</span>
        </div>
      </td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Calculate parcels for areas, GFA, FAR, BCR, etc</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">ctBld</td>
      <td style="padding:12px; border:1px solid #ddd;">Building Centroids</td>
      <td style="padding:12px; border:1px solid #ddd;">List of building footprint centroids</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Fp</td>
      <td style="padding:12px; border:1px solid #ddd;">Footprint</td>
      <td style="padding:12px; border:1px solid #ddd;">Footprint area per parcel</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">areaBld</td>
      <td style="padding:12px; border:1px solid #ddd;">Building Areas</td>
      <td style="padding:12px; border:1px solid #ddd;">List of building footprint area</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">BCR</td>
      <td style="padding:12px; border:1px solid #ddd;">BCR</td>
      <td style="padding:12px; border:1px solid #ddd;">Building Coverage Ratio</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">floorBld</td>
      <td style="padding:12px; border:1px solid #ddd;">Building Floors</td>
      <td style="padding:12px; border:1px solid #ddd;">List of building floors</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">GFA</td>
      <td style="padding:12px; border:1px solid #ddd;">GFA</td>
      <td style="padding:12px; border:1px solid #ddd;">Gross Floor Area per parcel</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">P</td>
      <td style="padding:12px; border:1px solid #ddd;">Parcels</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of parcel curves</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">FAR</td>
      <td style="padding:12px; border:1px solid #ddd;">FAR</td>
      <td style="padding:12px; border:1px solid #ddd;">Floor Area Ratio per parcel</td>
    </tr>
    <tr>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">MaxF</td>
      <td style="padding:12px; border:1px solid #ddd;">Max Floor</td>
      <td style="padding:12px; border:1px solid #ddd;">Maximum floors per parcel</td>
    </tr>

    <!-- Extrude Building -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Extrude_Building.png" alt="Extrude Building" style="height:25px; margin-bottom:5px;">
          <span>Extrude Building</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Extrude building curves based on types and floors</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Footprint curves</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">All</td>
      <td style="padding:12px; border:1px solid #ddd;">All Extrusions</td>
      <td style="padding:12px; border:1px solid #ddd;">All extruded volumes</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">T</td>
      <td style="padding:12px; border:1px solid #ddd;">Types</td>
      <td style="padding:12px; border:1px solid #ddd;">Building types: landed or tower</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Landed</td>
      <td style="padding:12px; border:1px solid #ddd;">Landed Extrusions</td>
      <td style="padding:12px; border:1px solid #ddd;">Extrusions for landed buildings</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">F</td>
      <td style="padding:12px; border:1px solid #ddd;">Floors</td>
      <td style="padding:12px; border:1px solid #ddd;">Floor count for each item</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Tower</td>
      <td style="padding:12px; border:1px solid #ddd;">Tower Extrusions</td>
      <td style="padding:12px; border:1px solid #ddd;">Extrusions for tower buildings</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">H</td>
      <td style="padding:12px; border:1px solid #ddd;">Floor Height</td>
      <td style="padding:12px; border:1px solid #ddd;">Height of one floor</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>

### Viewport Tools

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
      <th style="text-align:center; padding:8px; border:8px; border:1px solid #ddd; background-color: #e8e8e8;">Initial</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Name</th>
      <th style="text-align:center; padding:8px; border:1px solid #ddd; background-color: #e8e8e8;">Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- Custom Foreground Bar -->
    <tr>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Custom_Foreground_Bar.png" alt="Custom Foreground Bar" style="height:25px; margin-bottom:5px;">
          <span>Foreground Bar</span>
        </div>
      </td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Create custom foreground bar preview</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pos</td>
      <td style="padding:12px; border:1px solid #ddd;">Position</td>
      <td style="padding:12px; border:1px solid #ddd;">Start location for drawing bars</td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Labels</td>
      <td style="padding:12px; border:1px solid #ddd;">Labels</td>
      <td style="padding:12px; border:1px solid #ddd;">List of labels to display</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">List of values</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Color</td>
      <td style="padding:12px; border:1px solid #ddd;">Rectangle fill color</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Wd</td>
      <td style="padding:12px; border:1px solid #ddd;">Max Width</td>
      <td style="padding:12px; border:1px solid #ddd;">Maximum rectangle width in pixels</td>
    </tr>

    <!-- Custom Viewport Pie -->
    <tr>
      <td rowspan="5" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Design/D_Custom_Viewport_Pie.png" alt="Custom Viewport Pie" style="height:25px; margin-bottom:5px;">
          <span>Viewport Pie</span>
        </div>
      </td>
      <td rowspan="5" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Create custom pie chart preview</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pos</td>
      <td style="padding:12px; border:1px solid #ddd;">Position</td>
      <td style="padding:12px; border:1px solid #ddd;">Center of the pie chart</td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
      <td rowspan="5" style="border:1px solid #ddd;"></td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Labels</td>
      <td style="padding:12px; border:1px solid #ddd;">Labels</td>
      <td style="padding:12px; border:1px solid #ddd;">List of segment labels</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">List of segment values</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Colors</td>
      <td style="padding:12px; border:1px solid #ddd;">List of segment colors</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Rd</td>
      <td style="padding:12px; border:1px solid #ddd;">Radius</td>
      <td style="padding:12px; border:1px solid #ddd;">Radius of the pie chart</td>
    </tr>
  </tbody>
</table>



!!! Tip  "Tip"

    These tools are flexible, allowing road detail inputs to be modified through the provided .csv input files. This enables users to customize parameters, update design assumptions, and test multiple scenarios without altering the core model logic.


