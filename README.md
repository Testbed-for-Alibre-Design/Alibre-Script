# Alibre Script examples, demos and experiments.

## Overview

- Alibre-Script.Reflected
  - Python stub files generated using .NET reflection
- Alibre-Script-Code-Assistant
  - Alibre Script custom GPT
- Alibre-Script-VSCode
  - VS Code workspace for Alibre Script
- alibre-script.api.text
  - Alibre Script API in txt and CSV formats
- Alibre-Script-Stub-Files
  - Python stub files for use outside of Alibre Design
- alibre-script-library-examples
  - Library examples
- alibre-script-examples
  - Documentation examples

## Contents

```
C:.
│   Alibre-Script.code-workspace
│   LICENSE
│   README.md
│
├───Alibre-Script-Code-Assistant-main
│       001.py
│       002.py
│       003.py
│       004.py
│       005.py
│       006.py
│       007.py
│       008.py
│       009.py
│       README.md
│
├───alibre-script-examples
│       Alibre-Script-Examples.code-workspace
│       Assembly-Constraints.py
│       Bolt-Creator.py
│       Calculating-Length-of-Curves.py
│       Cap-Screw-ISO-4762-Bolts.py
│       Copy-sketch.py
│       Create-and-Modify-Global-Parameters.py
│       Create-Reference-Planes-Axes-and-Points.py
│       Creating-a-3D-Sketch-with-a-Spline-and-an-Arc.py
│       Creating-a-Cylinder-Between-Two-Points.py
│       Creating-and-Manipulating-Assemblies.py
│       Custom-Values-and-Settings-Window.py
│       Default-Reference-Geometry.py
│       Drop-Down-Lists.py
│       Everyone-Loves-a-Slinky.py
│       Gear-Example.py
│       Geodesic-Dome-Reference-Geometry.py
│       Getting-User-Input.py
│       Helical-spring.py
│       Import-points-from-a-CSV-file-rotate-them-and-connect-into-a-polyline.py
│       Importing-Files.py
│       Joint-Creator.py
│       List-All-Parts-in-an-Assembly-and-Sub-Assemblies.py
│       Lofting-with-a-Guide-Curve.py
│       Midplane-Extrusion.py
│       Mobius-Strip.py
│       Modify-an-Existing-Part.py
│       Parameters-with-Units.py
│       Pocket-Hole-Creator.py
│       Polygon-Incircle.py
│       Profile-and-Sweep-Path.py
│       Reading-from-a-Spreadsheet.py
│       README.md
│       Rectangular-hollow-formed-profiles.py
│       Reference-Geometry.py
│       Scaling-a-Sketch.py
│       Servo-Cam.py
│       Slice-a-Part.py
│       Square-hollow-formed-profiles.py
│       Supressing-Unsupressing-and-Removing-Features.py
│       Tool-Cutting.py
│       Triangle.py
│       Type-11-flanges-according-to-BS-EN-1092-PN16.py
│       Units.py
│       Useful-Dialogs.py
│       Wave-washer.py
│       Working-with-Configurations.py
│
├───alibre-script-library-examples
│   │   README.md
│   │
│   ├───Import and Export
│   │       MaxCellSize.jpg
│   │       NormalDeviation.jpg
│   │       Part Exporter.py
│   │       STL Exporter.py
│   │       SurfaceDeviation.jpg
│   │
│   ├───Mathematical
│   │       Equation Sketcher.py
│   │       EquationSketcher.png
│   │
│   ├───Mechanical
│   │       Gear Generator.py
│   │       GearGenerator.png
│   │
│   ├───Utilities
│   │       File Copier.py
│   │       Image to Python.py
│   │       Pattern Along.py
│   │       PatternAlong.png
│   │       Sketch Copier.py
│   │       SketchCopier.png
│   │
│   └───Woodworking
│           Joint Creator.py
│           JointCreatorIcon.png
│           Pocket Hole Creator.py
│           PocketHoleCreatorIcon.png
│
├───Alibre-Script-Stub-Files
│       AlibreScriptAPI_Mock.py
│       alibre_script_api.py
│       alibre_script_api_advanced_docs.pyi
│       alibre_script_api_docs.pyi
│       alibre_script_api_python27_docs.py
│       main.py
│       mock_api (Original).py
│       mock_api.py
│       README.md
│
├───Alibre-Script-VSCode
│       AlibreScript.py
│       AlibreScriptAPIVSCodeDemo.code-workspace
│       main.py
│       main3.py
│       NOTEBOOK.ipynb
│       README.md
│
├───alibre-script.api.text
│       alibre.script.api.txt
│       alibre.script.api2.csv
│       alibre.script.api2.txt
│       alibre.script.api3.csv
│       README.md
│
└───Alibre-Script.Reflected
    │   AlibreScript.Reflected.code-workspace
    │   generate.py
    │   image.png
    │   README.md
    │
    ├───bin
    │       AlibreScript.py
    │       AlibreScript2.py
    │       ex_0 copy.py
    │       ex_0.py
    │       ex_1.py
    │       main.py
    │       Notebook.ipynb
    │
    ├───output
    │       AssembledSubAssembly.py
    │       Assembly.py
    │       Axis.py
    │       Bspline.py
    │       Bspline3D.py
    │       Circle.py
    │       CircularArc.py
    │       CircularArc3D.py
    │       Configuration.py
    │       CSharp.py
    │       Edge.py
    │       Ellipse.py
    │       EllipticalArc.py
    │       Face.py
    │       Feature.py
    │       GearSketch.py
    │       GlobalParameters.py
    │       IAssembled.py
    │       IAxis.py
    │       IChamferable.py
    │       IConstrainable.py
    │       ICrossSection.py
    │       IFilletable.py
    │       IInstance.py
    │       IPlane.py
    │       IPoint.py
    │       ISelectableGeometry.py
    │       ISketchFigure.py
    │       ISketchFigure3D.py
    │       ISketchSurface.py
    │       ISweepPath.py
    │       Line.py
    │       Line3D.py
    │       Material.py
    │       Parameter.py
    │       Part.py
    │       Plane.py
    │       Point.py
    │       Polyline.py
    │       Polyline3D.py
    │       PolylinePoint.py
    │       PolylinePoint3D.py
    │       Sketch.py
    │       Sketch3D.py
    │       SketchPoint.py
    │       SketchPoint3D.py
    │       ThreeD.py
    │       TwoD.py
    │       Units.py
    │       Vertex.py
    │       Windows.py
    │
    ├───sources
    │       AlibreScript.API.AssembledSubAssembly.txt
    │       AlibreScript.API.Assembly.txt
    │       AlibreScript.API.Axis.txt
    │       AlibreScript.API.Bspline.txt
    │       AlibreScript.API.Bspline3D.txt
    │       AlibreScript.API.Circle.txt
    │       AlibreScript.API.CircularArc.txt
    │       AlibreScript.API.CircularArc3D.txt
    │       AlibreScript.API.Configuration.txt
    │       AlibreScript.API.CSharp.txt
    │       AlibreScript.API.Edge.txt
    │       AlibreScript.API.Ellipse.txt
    │       AlibreScript.API.EllipticalArc.txt
    │       AlibreScript.API.Face.txt
    │       AlibreScript.API.Feature.txt
    │       AlibreScript.API.GearSketch.txt
    │       AlibreScript.API.GlobalParameters.txt
    │       AlibreScript.API.IAssembled.txt
    │       AlibreScript.API.IAxis.txt
    │       AlibreScript.API.IChamferable.txt
    │       AlibreScript.API.IConstrainable.txt
    │       AlibreScript.API.ICrossSection.txt
    │       AlibreScript.API.IFilletable.txt
    │       AlibreScript.API.IInstance.txt
    │       AlibreScript.API.IPlane.txt
    │       AlibreScript.API.IPoint.txt
    │       AlibreScript.API.ISelectableGeometry.txt
    │       AlibreScript.API.ISketchFigure.txt
    │       AlibreScript.API.ISketchFigure3D.txt
    │       AlibreScript.API.ISketchSurface.txt
    │       AlibreScript.API.ISweepPath.txt
    │       AlibreScript.API.Line.txt
    │       AlibreScript.API.Line3D.txt
    │       AlibreScript.API.Material.txt
    │       AlibreScript.API.Parameter.txt
    │       AlibreScript.API.Part.txt
    │       AlibreScript.API.Plane.txt
    │       AlibreScript.API.Point.txt
    │       AlibreScript.API.Polyline.txt
    │       AlibreScript.API.Polyline3D.txt
    │       AlibreScript.API.PolylinePoint.txt
    │       AlibreScript.API.PolylinePoint3D.txt
    │       AlibreScript.API.Sketch.txt
    │       AlibreScript.API.Sketch3D.txt
    │       AlibreScript.API.SketchPoint.txt
    │       AlibreScript.API.SketchPoint3D.txt
    │       AlibreScript.API.ThreeD.txt
    │       AlibreScript.API.TwoD.txt
    │       AlibreScript.API.Units.txt
    │       AlibreScript.API.Vertex.txt
    │       AlibreScript.API.Windows.txt
    │
    └───test.packages
        ├───alibrescript_package
        │   │   setup.py
        │   │
        │   └───alibrescript_package
        │           AlibreScript.py
        │           __init__.py
        │
        └───alibrescript_windows_package
            │   setup.py
            │
            └───alibrescript_windows_package
                    Windows.py
                    __init__.py

```

ChatGPT Generated ReadMe's
- ["ChatGPT-README-0"](ChatGPT-README0.md)
- ["ChatGPT-README-1"](ChatGPT-README1.md)
- ["ChatGPT-README-2"](ChatGPT-README2.md)


All content and branding related to Alibre, Alibre Design, and Alibre Script, including any third-party contributions, are governed by their respective licensing agreements and are the intellectual property of Alibre, LLC.