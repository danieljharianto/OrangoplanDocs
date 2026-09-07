#Analysis
Analysis Tools allow designers to perform real-time analysis of spatial and urban performance within the model. The tools are divided into two categories: Geometric Analysis, for evaluating spatial properties such as area, density, parcel metrics, and dimensional relationships; and Network Analysis, for assessing connectivity, accessibility, and movement performance across street and path networks.

!!! Tip  "Important Tips"

    These tools are intended to support exploratory design and comparative analysis. Results should be interpreted as indicative rather than definitive and validated with authoritative data where required. Users are strongly encouraged to cross-check outputs against verified datasets, local regulations, and to review assumptions, input parameters, and data sources before drawing conclusions or making design decisions.


### Geometric Analysis

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
    <!-- Centroid -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Analysis/A_Centroid.png" alt="Centroid" style="height:25px; margin-bottom:5px;">
          <span>Centroid</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Analyze centroid each closed curve</td>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">C</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Curves</td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Closed curves to analyze</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ct</td>
      <td style="padding:12px; border:1px solid #ddd;">Centroids</td>
      <td style="padding:12px; border:1px solid #ddd;">Center points</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">A</td>
      <td style="padding:12px; border:1px solid #ddd;">Area</td>
      <td style="padding:12px; border:1px solid #ddd;">Area of closed curves</td>
    </tr>

    <!-- Convex Hull -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Analysis/A_Convex_Hull.png" alt="Convex Hull" style="height:25px; margin-bottom:5px;">
          <span>Convex Hull</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Create convex hull form points</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">C</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Curves</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Curves to compute convex hull</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Pts</td>
      <td style="padding:12px; border:1px solid #ddd;">Convex Hull Points</td>
      <td style="padding:12px; border:1px solid #ddd;">Points of the convex hull</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Hull</td>
      <td style="padding:12px; border:1px solid #ddd;">Convex Hull</td>
      <td style="padding:12px; border:1px solid #ddd;">Convex hull as a closed polyline</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">A</td>
      <td style="padding:12px; border:1px solid #ddd;">Area</td>
      <td style="padding:12px; border:1px solid #ddd;">Area of the convex hull</td>
    </tr>
  </tbody>
</table>

### Network Analysis

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
    <!-- Service Catchment -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Analysis/A_Service_Catchment.png" alt="Service Catchment" style="height:25px; margin-bottom:5px;">
          <span>Service Catchment</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Analyzes road service coverage based on search radius</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">P</td>
      <td style="padding:12px; border:1px solid #ddd;">Points</td>
      <td style="padding:12px; border:1px solid #ddd;">Origin points to analyze</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">L</td>
      <td style="padding:12px; border:1px solid #ddd;">Network Lengths</td>
      <td style="padding:12px; border:1px solid #ddd;">Total length of catchment within the search radius</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Network Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Network curves to analyze</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">B</td>
      <td style="padding:12px; border:1px solid #ddd;">Network Boundaries</td>
      <td style="padding:12px; border:1px solid #ddd;">Boundaries within the catchment radius</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">R</td>
      <td style="padding:12px; border:1px solid #ddd;">Search Radius</td>
      <td style="padding:12px; border:1px solid #ddd;">Catchment radius from origin points</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Shortest Path -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Analysis/A_Shortest_Path.png" alt="Shortest Path" style="height:25px; margin-bottom:5px;">
          <span>Shortest Path</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Computes the shortest path between two points along a network of curves</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">S</td>
      <td style="padding:12px; border:1px solid #ddd;">Start Point</td>
      <td style="padding:12px; border:1px solid #ddd;">Start point of the path</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Shortest Path Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Shortest path as a curves</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">E</td>
      <td style="padding:12px; border:1px solid #ddd;">End Point</td>
      <td style="padding:12px; border:1px solid #ddd;">End point of the path</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">L</td>
      <td style="padding:12px; border:1px solid #ddd;">Path Lengths</td>
      <td style="padding:12px; border:1px solid #ddd;">Shortest path lengths</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Network Curves</td>
      <td style="padding:12px; border:1px solid #ddd;">Network curves to analyze</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>


