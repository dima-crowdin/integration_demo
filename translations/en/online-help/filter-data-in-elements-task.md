# Filter data in elements

You can apply filters to refine the data used to calculate KPI and indicators in elements. You can filter using time and / or dimensions configured in your ERP such as, department, currency, project or document type.

Time filters are applied by default to all elements and cannot be deleted. All elements have a predefined time unit that is automatically applied when using a default dashboard, and any time the element is newly added to a dashboard. You can change these predefined time units by following the steps listed below in the editing time filters section.

<details>
<summary>Filtering using the X axis</summary>

You can apply filters by changing the X axis denominator, directly on the chart:

1.  Hover over the description of the X axis (can be for example "Months", "Years", "Currency"). Click.
2.  A **Change dimension** pop-up window will appear listing the options available in your ERP to be used as X axis for the element. You can select time units (Months, Quarters, Years) or specific dimensions from the ERP (Account, Currency, or for example Cost centre, Location, Product group, Department etc.).
3.  Select what dimension you want to apply by clicking it.
4.  The X axis change is made automatically following this selection, the chart or table will be refreshed.
</details>

<details>
<summary>Adding and editing time filters</summary>

1.  Place the cursor over the element you want to apply filter(s) to, and a menu of icons will appear in the top right corner of the element.
2.  Click on the funnel icon. This will open a new window which appears on the right of your screen.
3.  The time filter is applied by default. You cannot remove the time filter.
4.  You can define the time period using **Dynamic range** where filter values are defined counting back and in the future, from the current date. As a result the time interval both in the past and in the future changes as the current system date changes. Both the **Last** option and the **Next** option can be used independently.  

    For example, assuming we are now in June and in the **Last** field we put 4 and in the **Next** field we put 3, then the time range displayed by the widget will be MAR, APR, MAY, JUN, JUL, AUG and SEP. If the **Next** field is filled in, the option **Include current period** is automatically set and cannot be deselected. If the **Next** field is not filled in, you can deselect the **Include current period** check box.
5.  You can define the time period using also **Static range** where filter values are defined regardless of the current date, and remain unchanged as current date changes. In this section you can select specific months, quarters and years. The service will list here those time units for which it has data. For ease of use the current time unit is marked in blue.
    *   Click on the time unit you want to set (Month, Quarter or Year)
    *   One or two selection boxes will appear just below it. One box will appear for chart types that can display just one value, like Gauge and Number. Two boxes will appear for all chart types that can display several values at once
    *   Click on the calendar button from the right end of the selection box. A drop-down window will appear containing the calendar format for the selected time unit
    *   You can navigate between time periods by clicking the left and right arrows near the calendar's title
    *   Select the time unit from the calendar by clicking it, after clicking the calendar drop-down window will automatically disappear
6.  Select or input the time units you want to filter for and the element data will be refreshed instantly. The window with filtering options will remain open.
7.  There is an **Include current period** check box at the top of the time periods section. If you select it, then the current period will be included in the selected period. For example if the current month is April, and you select the Last 3 months option and leave unchecked the **Include current period** box, then your time filter will be set to January-February-March. But if you select the Last 3 months option and check the **Include current period** box, then your time filter will be February-March-April.
8.  The option **Stack previous periods** will show in each period the cumulated values for all the previous periods included in the time filter of a KPI. For example having Cost of sales KPI and the time period January - March 2017, you have the following values when stack previous periods is not selected: January – 100, February – 100 and March – 100\. After you select this option you will get: January – 100, February – 200 and March – 300.
9.  You can close the filtering options window by clicking the **X** in the top right corner.
</details>

<details>
<summary>Adding and editing dimension filters</summary>

1.  Place the cursor over the element you want to apply filter(s) to, and a menu of icons will appear in the top right corner of the element.
2.  Click on the funnel icon. This will open a new window which appears on the right of your screen.
3.  Click the **Dimensions** header or on the blue arrow near it, located in the lower half of the filtering window. The available dimensions will be listed below.
4.  You can apply filters for dimensions which are configured in the ERP, for example account, currency, department, cost center.
5.  You can set filter values as follows:
    *   Click on the description of the dimension you want to filter on, or on the blue arrow near it
    *   A list will appear with all values in use for this dimension
    *   You can select or deselect values one by one, or all by checking the **Select all** box, or you can deselect all by unchecking the **Select all** box
    *   If you are looking for a specific value, you can use the search option available for each dimension. Click inside the **Search** box located below the dimension header, and start typing the name you are looking for. Search results are filtered and displayed as you type
6.  You can close the filtering options window by clicking the **X** in the top right corner.
</details>
