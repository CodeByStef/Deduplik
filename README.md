# ![logo](https://github.com/CodeByStef/Deduplik/blob/main/Assets/Deduplik.png) Deduplik
Deduplik ⁕ A graphical tool to clearly visualize duplicate files location and rapidly tag which one to keep and which one to remove.

Matching duplicates is done with an efficient comparison of the file content; not with weak methods such as file names or dates.


# Getting started:
Unzip the release to the folder of your choice.
Look for and launch "Primordial.exe".

You'll need the .NET Desktop Runtime 8.0 installed (https://dotnet.microsoft.com/en-us/download/dotnet).

Interacting with Deduplik is done with the mouse.  
Left click: Object selection.
Richt click: Action popup.

# Demo files
To get a quick start using Deduplik, unzip “Demo files.zip” and scan it.
The demo files are set with a few duplicate scenarios.




```mermaid
graph LR;

    A[C:\]
    B[FolderB];
    B2[FolderBB];
    C[FolderC];
    C2[FolderCC];
    F1([FileA]);
    F2([FileAB]);
    F3([FileAC]);
    F4([FileD]);

    A-->C;
    A-->B;
    C-->C2;
    B-->B2;
    B2-->F1;
    B-->F2;
    C-->F3;
    C2-->F4;

    subgraph Unique files
    U1([FileA]);
    U4([FileD]);
    end

    subgraph dups [Duplicate files]
    F2([FileAB]);
    F3([FileAC]);
    style F2 stroke:#f00
    style F3 stroke:#f00
    style dups stroke:#f00, fill:#fee
    end

    F1-->U1;
    F2-->U1;
    F3-->U1;
    F4-->U4;
```
