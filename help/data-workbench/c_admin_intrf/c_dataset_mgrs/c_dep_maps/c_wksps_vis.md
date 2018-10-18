---
description: Conceptual information about workspaces and visualizations.
seo-description: Conceptual information about workspaces and visualizations.
seo-title: Workspaces and visualizations
solution: Analytics
title: Workspaces and visualizations
topic: Data workbench
uuid: cc041986-16ca-4326-b570-c87698309156
index: y
internal: n
snippet: y
---

# Workspaces and visualizations

Conceptual information about workspaces and visualizations.

The following figure shows a dependency map whose nodes represent the workspaces, reports, menu options, and globe layers defined in the profile. This option works only if the [!UICONTROL Query Model] display option is enabled.

>[!NOTE]
>
>If the [!UICONTROL Query Model] display option is not enabled when you choose the [!UICONTROL Workspaces and Visualizations] display option, an error message appears.

![](assets/vis_DependencyMap_QueryModelandWorkspaces.png)

* A gray node represents a workspace or a report. 
* A yellow-green node represents a menu option. 
* A red node represents a workspace, report, menu option, or globe layer with a broken or circular dependency or other error.

>[!NOTE]
>
>Because the dependency map is designed to accommodate acyclic dependencies, nodes involved in circular dependencies may not display properly on the map. You can search for circular dependencies by typing “circular dependency” in the [!UICONTROL Search] text box. For more information about the [!UICONTROL Search] feature, see [Searching Within a Map](../../../c_admin_intrf/c_dataset_mgrs/c_dep_maps/t_srch_map.md#task_A1E7065A538D46C78A7D28676D880DFB).

For descriptions of other nodes on the map, see [Query Model Components](../../../c_admin_intrf/c_dataset_mgrs/c_dep_maps/c_qry_mod_comp.md#concept_32C6DADD32F74179B026C7E96D47710F). 