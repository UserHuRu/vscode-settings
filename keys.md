本文以 macOS 系统作为示例说明，键位对应关系如下：

|  macOS | Windows
| ---|---
| ⌘ command | ctrl
| ⌥ option | alt
| ⇧ shift | shift

### 官方完整键位表

- [macOS](./files/keyboard-shortcuts-macos.pdf)
- [Windows](./files/keyboard-shortcuts-windows.pdf)
- [Linux](./files/keyboard-shortcuts-linux.pdf)

更多内容，请参考：[https://code.visualstudio.com/docs/getstarted/keybindings](https://code.visualstudio.com/docs/getstarted/keybindings)

### 常用快捷键：

<table>
    <tr>
        <th>分类</th>
        <th>按键</th>
        <th>说明</th>
        <th>命令</th>
    </tr>
    <tr>
        <td rowspan="16">编辑</td>
        <td>⌘X</td>
        <td>剪切鼠标选择的内容或当前行</td>
        <td>editor.action.clipboardCutAction</td>
    </tr>
    <tr>
        <td>⌘C</td>
        <td>复制鼠标选择的内容或当前行</td>
        <td>editor.action.clipboardCopyAction</td>
    </tr>
    <tr>
        <td>⌘V</td>
        <td>粘贴</td>
        <td></td>
    </tr>
    <tr>
        <td>⇧⌘K</td>
        <td>删除当前行或选择的内容</td>
        <td>editor.action.deleteLines</td>
    </tr>
    <tr>
        <td>⌘Enter</td>
        <td>在当前行紧邻的下一行插入新行</td>
        <td>editor.action.insertLineAfter</td>
    </tr>
    <tr>
        <td>⇧⌘Enter</td>
        <td>在当前行紧邻的上一行插入新行</td>
        <td>editor.action.insertLineBefore</td>
    </tr>
    <tr>
        <td>⌥↓</td>
        <td>向下移动当前行或已选择的行</td>
        <td>editor.action.moveLinesDownAction</td>
    </tr>
    <tr>
        <td>⌥↑</td>
        <td>向上移动当前行或已选择的行</td>
        <td>editor.action.moveLinesUpAction</td>
    </tr>
    <tr>
        <td>⇧⌥↓</td>
        <td>在下部复制并插入当前行或已选择的行</td>
        <td>editor.action.copyLinesDownAction</td>
    </tr>
    <tr>
        <td>⇧⌥↑</td>
        <td>在上部复制并插入当前行或已选择的行</td>
        <td>editor.action.copyLinesUpAction</td>
    </tr>
    <tr>
        <td>⌘D</td>
        <td>鼠标选择一个单词或语句块，使用此快捷键跳转并选中下一个相同的内容</td>
        <td>editor.action.addSelectionToNextFindMatch</td>
    </tr>
    <tr>
        <td>⇧⌥I</td>
        <td>在每个已选择行的尾部显示插入光标</td>
        <td>editor.action.insertCursorAtEndOfEachLineSelected</td>
    </tr>
    <tr>
        <td>⇧⌘L</td>
        <td>选中与当前已选择内容相同的所有字符</td>
        <td>editor.action.selectHighlights</td>
    </tr>
    <tr>
        <td>⌘I</td>
        <td>选中当前行</td>
        <td>expandLineSelection</td>
    </tr>
    <tr>
        <td>⌘/</td>
        <td>添加或移除行注释</td>
        <td>editor.action.commentLine</td>
    </tr>
    <tr>
        <td>⇧⌥A</td>
        <td>添加或移除块级注释</td>
        <td>editor.action.blockComment</td>
    </tr>
    <tr>
        <td rowspan="6">搜索</td>
        <td>⌘F</td>
        <td>当前文件中查找</td>
        <td></td>
    </tr>
    <tr>
        <td>⌘⌥F</td>
        <td>当前文件中查找并替换</td>
        <td></td>
    </tr>
    <tr>
        <td>⇧⌘F</td>
        <td>全局文件中查找</td>
        <td>workbench.view.search</td>
    </tr>
    <tr>
        <td>⇧⌘H</td>
        <td>全局文件中查找并替换</td>
        <td>workbench.action.replaceInFiles</td>
    </tr>
    <tr>
        <td>⌥↓</td>
        <td>切换历史搜索关键字的下一个</td>
        <td>search.history.showNext</td>
    </tr>
    <tr>
        <td>⌥↑</td>
        <td>切换历史搜索关键字的上一个</td>
        <td>search.history.showPrevious</td>
    </tr>
    <tr>
        <td rowspan="11">跳转</td>
        <td>⌃G</td>
        <td>跳转到下一个搜索匹配项</td>
        <td>workbench.action.gotoLine</td>
    </tr>
    <tr>
        <td>⌘P</td>
        <td>快速定位打开文件</td>
        <td>workbench.action.quickOpen</td>
    </tr>
    <tr>
        <td>⇧⌘O</td>
        <td>快速定位到当前文件中指定的标记（函数、变量...），同 <code>⌘P + @</code></td>
        <td>workbench.action.gotoSymbol</td>
    </tr>
    <tr>
        <td>⌃⇧Tab</td>
        <td>在已打开的文件之间快速切换</td>
        <td>workbench.action.openPreviousRecentlyUsedEditorInGroup</td>
    </tr>
    <tr>
        <td>⇧⌘\</td>
        <td>在一个括号的首尾进行切换</td>
        <td>editor.action.jumpToBracket</td>
    </tr>
    <tr>
        <td>⌘↓</td>
        <td>文件头部</td>
        <td>cursorTop</td>
    </tr>
    <tr>
        <td>⌘↑</td>
        <td>文件尾部</td>
        <td>cursorBottom</td>
    </tr>
    <tr>
        <td>⌘←</td>
        <td>当前行首部</td>
        <td></td>
    </tr>
    <tr>
        <td>⌘→</td>
        <td>当前行尾部</td>
        <td></td>
    </tr>
    <tr>
        <td>⌃-</td>
        <td>下一个 tab 栏</td>
        <td>workbench.action.navigateBack</td>
    </tr>
    <tr>
        <td>⌃⇧-</td>
        <td>上一个 tab 栏</td>
        <td>workbench.action.navigateForward</td>
    </tr>
    <tr>
        <td rowspan="11">文件</td>
        <td>⌘N</td>
        <td>新建文件</td>
        <td>workbench.action.files.newUntitledFile</td>
    </tr>
    <tr>
        <td>⌘O</td>
        <td>打开文件或文件夹</td>
        <td></td>
    </tr>
    <tr>
        <td>⌥⌘T</td>
        <td>关闭当前文件以外的其它文件</td>
        <td></td>
    </tr>
    <tr>
        <td>⌘S</td>
        <td>保存</td>
        <td>workbench.action.files.save</td>
    </tr>
    <tr>
        <td>⌥⌘S</td>
        <td>保存所有</td>
        <td>workbench.action.files.saveAll</td>
    </tr>
    <tr>
        <td>⇧⌘S</td>
        <td>另存为</td>
        <td>workbench.action.files.saveAs</td>
    </tr>
    <tr>
        <td>⌘K U</td>
        <td>关闭已保存的文件</td>
        <td></td>
    </tr>
    <tr>
        <td>⌘K W</td>
        <td>关闭所有文件</td>
        <td></td>
    </tr>
    <tr>
        <td>⌘K R</td>
        <td>打开系统窗口，定位当前已打开的文件</td>
        <td>workbench.action.files.revealActiveFileInWindows</td>
    </tr>
    <tr>
        <td>⌘K P</td>
        <td>复制当前文件的绝对路径，同 <code>⌥⌘C</code></td>
        <td></td>
    </tr>
    <tr>
        <td>⌘K O</td>
        <td>在创建的新窗口显示当前已打开的文件</td>
        <td>workbench.action.files.showOpenedFileInNewWindow</td>
    </tr>
    <tr>
        <td rowspan="5">窗口</td>
        <td>⇧⌘N</td>
        <td>打开新窗口</td>
        <td>workbench.action.newWindow</td>
    </tr>
    <tr>
        <td>⌘\</td>
        <td>分割编辑器窗口，最多支持 3 个</td>
        <td>workbench.action.splitEditor</td>
    </tr>
    <tr>
        <td>⌘1</td>
        <td>聚焦第一个分割出来的编辑器窗口</td>
        <td>workbench.action.focusFirstEditorGroup</td>
    </tr>
    <tr>
        <td>⌘2</td>
        <td>聚焦第二个分割出来的编辑器窗口</td>
        <td>workbench.action.focusSecondEditorGroup</td>
    </tr>
    <tr>
        <td>⌘3</td>
        <td>聚焦第三个分割出来的编辑器窗口</td>
        <td>workbench.action.focusThirdEditorGroup</td>
    </tr>
    <tr>
        <td rowspan="9">显示</td>
        <td>⌃⌘F</td>
        <td>切换全屏</td>
        <td>workbench.action.toggleFullScreen</td>
    </tr>
    <tr>
        <td>⌘B</td>
        <td>显示隐藏侧边栏</td>
        <td>workbench.action.toggleSidebarVisibility</td>
    </tr>
    <tr>
        <td>⇧⌘F</td>
        <td>显示侧边搜索栏</td>
        <td>workbench.view.search</td>
    </tr>
    <tr>
        <td>⌃⇧G</td>
        <td>显示侧边版本控制栏</td>
        <td>workbench.view.scm</td>
    </tr>
    <tr>
        <td>⇧⌘D</td>
        <td>显示侧边 Debug 栏</td>
        <td>workbench.view.debug</td>
    </tr>
    <tr>
        <td>⇧⌘X</td>
        <td>显示侧边扩展栏</td>
        <td>workbench.view.extensions</td>
    </tr>
    <tr>
        <td>⇧⌘U</td>
        <td>显示、隐藏底部输出面板</td>
        <td>workbench.action.output.toggleOutput</td>
    </tr>
    <tr>
        <td>⌃Q</td>
        <td>在不同面板间快速切换</td>
        <td>workbench.action.quickOpenView</td>
    </tr>
    <tr>
        <td>⌃`</td>
        <td>显示、隐藏底部 terminal 面板</td>
        <td>workbench.action.terminal.toggleTerminal</td>
    </tr>
    <tr>
        <td rowspan="8">Debug</td>
        <td>F9</td>
        <td>添加或移除断点</td>
        <td>editor.debug.action.toggleBreakpoint</td>
    </tr>
    <tr>
        <td>F5</td>
        <td>开始调试</td>
        <td>workbench.action.debug.start</td>
    </tr>
    <tr>
        <td>F5</td>
        <td>继续</td>
        <td>workbench.action.debug.continue</td>
    </tr>
    <tr>
        <td>F6</td>
        <td>暂停</td>
        <td>workbench.action.debug.pause</td>
    </tr>
    <tr>
        <td>F11</td>
        <td>步入</td>
        <td>workbench.action.debug.stepInto</td>
    </tr>
    <tr>
        <td>⇧F11</td>
        <td>步出</td>
        <td>workbench.action.debug.stepOut</td>
    </tr>
    <tr>
        <td>F10</td>
        <td>跳过</td>
        <td>workbench.action.debug.stepOver</td>
    </tr>
    <tr>
        <td>⇧F5</td>
        <td>停止调试</td>
        <td>workbench.action.debug.stop</td>
    </tr>
</table>
