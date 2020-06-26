---
title: Office 脚本 API 参考
description: Office 脚本 JavaScript Api 概述。
ms.date: 06/17/2020
ms.openlocfilehash: 5634d0e5f68464655054ad1c09eb7931e0da62d4
ms.sourcegitcommit: 163b26a43411ad7f13a01237efe9b8d6de656b47
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/25/2020
ms.locfileid: "44880805"
---
# <a name="office-scripts-api-reference"></a>Office 脚本 API 参考

Office 脚本 API 允许您在 web 上的 Excel 中自动执行常见任务。 使用此参考文档可了解有关可用于脚本的类、方法和其他类型的详细信息。 可通过 Office 脚本访问的所有对象都可以在页面左侧的目录中找到。

> [!NOTE]
> 如果你要查找用于开发 Office 外接程序的 JavaScript Api，请访问[Office 外接程序 JAVASCRIPT api 参考](/javascript/api/overview?view=excel-js-preview)。

## <a name="common-classes"></a>公共类

以下列表细分了 Office 脚本对象模型的基础知识。 这将显示常见类以及它们之间的关系。

- 一个 [Workbook](/javascript/api/office-scripts/excel/excelscript.workbook) 包含一个或多个 [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet)。
- [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet) 可通过 [Range](/javascript/api/office-scripts/excel/excelscript.range) 对象访问单元格。
- [Range](/javascript/api/office-scripts/excel/excelscript.range) 代表一组连续的单元格。
- [Range](/javascript/api/office-scripts/excel/excelscript.range) 用于创建和放置 [Table](/javascript/api/office-scripts/excel/excelscript.table)、[Chart](/javascript/api/office-scripts/excel/excelscript.chart) 和 [Shape](/javascript/api/office-scripts/excel/excelscript.shape) 以及其他数据可视化或组织对象。
- [工作表](/javascript/api/office-scripts/excel/excelscript.worksheet)包含使用单个工作表中存在的那些对象填充的数组。
- [工作簿](/javascript/api/office-scripts/excel/excelscript.workbook)包含所有工作簿的一些数据对象的数组。

有关 Office 脚本对象模型的详细信息，请访问[web 上 Excel 中 Office 脚本的脚本基础](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>另请参阅

- [关于 Office 脚本](/office/dev/scripts/overview/excel)
- [在 Excel 网页版中录制、编辑和创建 Office 脚本](/office/dev/scripts/tutorials/excel-tutorial)
- [Excel 网页版中 Office 脚本的脚本基础](/office/dev/scripts/develop/scripting-fundamentals)