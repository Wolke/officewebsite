
hi:

讀書會官方網站製作 v1.0

目前製作項目有

componets中APP.js加入

import injectTapEventPlugin from 'react-tap-event-plugin';
import MuiThemeProvider from 'material-ui/styles/MuiThemeProvider';
import getMuiTheme from 'material-ui/styles/getMuiTheme';
import darkBaseTheme from 'material-ui/styles/baseThemes/darkBaseTheme';

並包一層
<MuiThemeProvider muiTheme={getMuiTheme(darkBaseTheme)}>
在<IntlProvider> 之上

其次修改header 加入一個 import AppBar from 'material-ui/AppBar';

但目前不知道要如何使用state 在components 之中

public 底下建立要使用的images/資料夾 當在 npm start 自動會copy到 build資料夾中

實作一個home 使用 material-ui 的card 成功使用 
