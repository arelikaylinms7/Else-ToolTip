# Else-ToolTip
Local $tInfo = DllStructCreate($tagNMLISTVIEW, $lParam) If $tInfo.Item = 5 And $tInfo.SubItem = 2 Then ToolTip("Infos displayed here...") Else ToolTip("")
