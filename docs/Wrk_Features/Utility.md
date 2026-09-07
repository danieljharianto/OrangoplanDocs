#Utility
Utility Tools support Rhino-object interoperability and workflow management across the modeling environment. The tools are divided into three categories: Rhino Reference, for linking and managing Rhino geometry by layer or color; List Matching, for aligning and dispatching datasets against a mask list; and Object Attributes, for baking, editing, and extracting geometric and non-geometric attributes.

### Rhino Reference

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
    <!-- Reference by Layer -->
    <tr>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Reference_by_Layer.png" alt="Reference by Layer" style="height:25px; margin-bottom:5px;">
          <span>Ref Layer</span>
        </div>
      </td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Reference Rhino objects by layer. Toggles: Sublayers &ndash; include child layers; Remap &ndash; renumber output branches to sequential {0},{1},{2},...</td>
      <td rowspan="4" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">L</td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Input Layer</td>
      <td rowspan="4" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Layer name to query</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Geo</td>
      <td style="padding:12px; border:1px solid #ddd;">Geometry</td>
      <td style="padding:12px; border:1px solid #ddd;">Geometry from layers, one branch per layer (branch numbering depends on the Remap toggle)</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Guid</td>
      <td style="padding:12px; border:1px solid #ddd;">Object IDs</td>
      <td style="padding:12px; border:1px solid #ddd;">Object IDs from Rhino &ndash; feed this into Edit/Extract Object Attributes, not the Geometry output</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">LPath</td>
      <td style="padding:12px; border:1px solid #ddd;">Layer Paths</td>
      <td style="padding:12px; border:1px solid #ddd;">Full layer path per branch</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">LName</td>
      <td style="padding:12px; border:1px solid #ddd;">Layer Name</td>
      <td style="padding:12px; border:1px solid #ddd;">Child layer name only, without its parent path</td>
    </tr>

    <!-- Reference by Color -->
    <tr>
      <td rowspan="2" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Reference_by_Color.png" alt="Reference by Color" style="height:25px; margin-bottom:5px;">
          <span>Ref Color</span>
        </div>
      </td>
      <td rowspan="2" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Reference Rhino object by its color</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">C</td>
      <td style="padding:12px; border:1px solid #ddd;">Color</td>
      <td style="padding:12px; border:1px solid #ddd;">Target color to match</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Obj</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects</td>
      <td style="padding:12px; border:1px solid #ddd;">Objects from matching color</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">T</td>
      <td style="padding:12px; border:1px solid #ddd;">Tolerance</td>
      <td style="padding:12px; border:1px solid #ddd;">Color matching tolerance</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Idx</td>
      <td style="padding:12px; border:1px solid #ddd;">Color Index</td>
      <td style="padding:12px; border:1px solid #ddd;">Index of matching color</td>
    </tr>
  </tbody>
</table>

### List Matching

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
    <!-- Match List Geo -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Match_List_Geometry.png" alt="Match List Geo" style="height:25px; margin-bottom:5px;">
          <span>Match List Geo</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Match text tree against a mask list text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Text</td>
      <td style="padding:12px; border:1px solid #ddd;">Text Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of input text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bool</td>
      <td style="padding:12px; border:1px solid #ddd;">Boolean Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of boolean result</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Mask</td>
      <td style="padding:12px; border:1px solid #ddd;">Mask List</td>
      <td style="padding:12px; border:1px solid #ddd;">List of match mask strings</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Matched Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Matched Tree Result</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of dispatched items based on match list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">M</td>
      <td style="padding:12px; border:1px solid #ddd;">Matches List</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree to dispatch using masking results</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Match List Text -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Match_List_Text.png" alt="Match List Text" style="height:25px; margin-bottom:5px;">
          <span>Match List Text</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Match text tree against a mask list text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Text</td>
      <td style="padding:12px; border:1px solid #ddd;">Text Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of input text</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Bool</td>
      <td style="padding:12px; border:1px solid #ddd;">Boolean Tree</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of boolean match mask results</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Mask</td>
      <td style="padding:12px; border:1px solid #ddd;">Mask List</td>
      <td style="padding:12px; border:1px solid #ddd;">List of match mask strings</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Matched Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Tree of dispatched items based on match list</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">M</td>
      <td style="padding:12px; border:1px solid #ddd;">Matches List</td>
      <td style="padding:12px; border:1px solid #ddd;">List to dispatch using masking results</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>
  </tbody>
</table>

### Object Attributes

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
    <!-- Bake with Attributes -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Bake_With_Attributes.png" alt="Bake with Attributes" style="height:25px; margin-bottom:5px;">
          <span>Bake Attrs</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Bakes GH geometry into the Rhino document with user-text attributes in one step</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Geo</td>
      <td style="padding:12px; border:1px solid #ddd;">Geometry</td>
      <td style="padding:12px; border:1px solid #ddd;">GH geometry to bake into the Rhino document</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">ID</td>
      <td style="padding:12px; border:1px solid #ddd;">Object ID</td>
      <td style="padding:12px; border:1px solid #ddd;">GUID of each baked object</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">K</td>
      <td style="padding:12px; border:1px solid #ddd;">Keys</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute keys</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Stat</td>
      <td style="padding:12px; border:1px solid #ddd;">Status</td>
      <td style="padding:12px; border:1px solid #ddd;">Operation status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">V</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute values</td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
      <td style="border:1px solid #ddd;"></td>
    </tr>

    <!-- Extract Object Attributes -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Extract_Object_Attributes.png" alt="Extract Object Attributes" style="height:25px; margin-bottom:5px;">
          <span>Extract Attributes</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Extracts object attribute key–value pairs from a referenced Rhino object</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">ID</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">GUID</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Object GUID as string (from Reference by Layer's Object IDs output)</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Key</td>
      <td style="padding:12px; border:1px solid #ddd;">Keys</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute keys</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Val</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute values</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">Ref</td>
      <td style="padding:12px; border:1px solid #ddd;">Referenced Layer</td>
      <td style="padding:12px; border:1px solid #ddd;">Object's layer name</td>
    </tr>

    <!-- Edit Object Attributes -->
    <tr>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">
        <div style="display:flex; flex-direction:column; align-items:center;">
          <img src="../../assets/Utility/U_Edit_Object_Attributes.png" alt="Edit Object Attributes" style="height:25px; margin-bottom:5px;">
          <span>Edit Attributes</span>
        </div>
      </td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Edits object attribute key–value pairs on a referenced Rhino object</td>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">ID</td>
      <td style="padding:12px; border:1px solid #ddd;">GUID</td>
      <td style="padding:12px; border:1px solid #ddd;">Object GUID as string (from Reference by Layer's Object IDs output)</td>
      <td rowspan="3" style="text-align:center; padding:12px; border:1px solid #ddd; vertical-align:middle;">Stat</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Status</td>
      <td rowspan="3" style="padding:12px; border:1px solid #ddd; vertical-align:middle;">Operation status message</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">K</td>
      <td style="padding:12px; border:1px solid #ddd;">Keys</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute keys</td>
    </tr>
    <tr>
      <td style="text-align:center; padding:12px; border:1px solid #ddd;">V</td>
      <td style="padding:12px; border:1px solid #ddd;">Values</td>
      <td style="padding:12px; border:1px solid #ddd;">Attribute values</td>
    </tr>
  </tbody>
</table>
