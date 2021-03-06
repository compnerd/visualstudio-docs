---
title: Options, Text Editor, F#, Code Fixes
ms.date: 01/16/2019
ms.prod: visual-studio-dev15
ms.topic: reference
f1_keywords:
  - "VS.ToolsOptionsPages.Text_Editor.FSharp.Code_Fixes"
author: gewarren
ms.author: gewarren
manager: douge
ms.workload:
  - "dotnet"
---
# Options, Text Editor, F#, Code Fixes

Use the **Code Fixes** options page to specify the settings that can help identify code errors and offer solutions. To access this options page, choose **Tools** > **Options**, and then choose **Text Editor** > **F#** > **Code Fixes**.

## Code Fixes

- **Simplify names (remove unnecessary qualifiers)**

   If this check box is selected, fully qualified names are simplified when the qualifications aren't necessary, such as for a member of a frequently used namespace.

- **Always place open statements at the top level**

   If this check box is selected and you type an open statement in the code, it's put at the top level.

- **Remove unused open statements**

   If this check box is selected, open statements in the current file that aren't used are removed.

- **Analyze and suggest fixes for unused values**

   If this check box is selected, the tool recognizes a value that isn't being used in the code. Then, if you hover over the unused value, it recommends ways in which you can use the value.

## See also

- [General, Environment, Options Dialog Box](../../ide/reference/general-environment-options-dialog-box.md)
- [Find code changes and other history with CodeLens](../../ide/find-code-changes-and-other-history-with-codelens.md)