## TORS definitions

TORS ontology for torsional vibration.

Base URL: https://tors.twinschema.org

URL for the term is formed by combining base URL and term path.

For example, in case of a Disk: https://tors.twinschema.org + Disk = https://ddt.twinschema.org/Disk

| Term | Term path| Description |
| ------------- | ------------- | ------------- |
| Elements | elements | List of elements the component consists of. For example, disks and shafts. |
| Disk | Disk | Disk element. |
| Damping | damping | Viscous damping coefficient of the disk. [Nms/rad] |
| Inertia | inertia | Moment of inertia of the disk. [kgm^2] |
| In coordinate | inCoordinate | The input coordinate of the element. |
| Out coordinate | outCoordinate | The output coordinate of the element. |
| Stiffness | stiffness | Stiffness of the element. [Nm/rad] |
| Length | length | Length of element, such as shaft. [m]|
| Inner diameter | innerDiameter | Inner diameter of an element, such as shaft element. [mm] |
| Outer diameter | outerDiameter | Outer diameter of an element, such as shaft element. [mm] |
| Properties | properties | Properties of an entity, such as component. Property can be, for example, excitations of a component in ccertain RPMs. |
| Excitation | Excitation | Type of object that defines excitation(s) of an entity, such as component. |
| Excitations in RPM | excitationValuesRpmPercentage | Excitations are presented as a list of two-item lists that contain the RPM multiple and the value of excitation in percentages. |
| Linspace start | startLinspace | The starting value of [Linspace function](https://numpy.org/doc/stable/reference/generated/numpy.linspace.html). |
| Linspace stop | stopLinspace | The stopping value of [Linspace function](https://numpy.org/doc/stable/reference/generated/numpy.linspace.html). |
| Linspace num | numLinspace | The number of elements generated by [Linspace function](https://numpy.org/doc/stable/reference/generated/numpy.linspace.html). |
| Linspace RPM | rpmLinspace | Defines RPMs used for analysis in linspace format. Expects Linspace start, Linspace stop, and Linspace num. |
| Vibrational torque amplitude analysis | TorqueAmplitudeAnalysis | Type of analysis run: Vibrational torque amplitude analysis. |