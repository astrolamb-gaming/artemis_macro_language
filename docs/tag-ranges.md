# The Ranges, Range and Item tag

## Ranges
The ranges tag is defined under the mission_data tag
ranges define a set of data for use with [repeat tags](tag-repeat.md) and macro statements.


``` xml
<ranges>
    <range name="AllShips">
        . . .
    </range>
</ranges>

``` xml
<mission_data version="1.0">
  <ranges>
    <range name="AllShips">
      <item ship="Artemis" sideValue="10" />
      <item ship="Intrepid" sideValue="11" />
      <item ship="Aegis" sideValue="4" />
      <item ship="Horatio" sideValue="5" />
      <item ship="Excalibur" sideValue="6" />
      <item ship="Hera" sideValue="7" />
      <item ship="Ceres" sideValue="8" />
      <item ship="Diana" sideValue="9" />
    </range>

    <range name="Eggs">
      <item egg="egg1" seconds="25" playerCount="0" x="50000" y="10" z="5000" />
      <item egg="egg2" seconds="30" playerCount="3.0" x="49000" y="3" z="49000" />
      <item egg="egg3" seconds="35" playerCount="4.0" x="51000" y="3" z="51000" />
      <item egg="egg4" seconds="35" playerCount="6.0" x="49000" y="3" z="5100" />
      <item egg="egg5" seconds="35" playerCount="7.0" x="51000" y="3" z="49000" />
    </range>
  </ranges>
</mission_data>
```