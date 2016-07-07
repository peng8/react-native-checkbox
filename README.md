# react-native-checkbox

下载 JS文件 导入到项目中

import CheckBox from './common/checkbox';

初始化

<CheckBox
     ref={(c)=>this.initCheckBoxData(c)}
     label=""
     checked={false}
     value={rowID}
     style={styles.check}
     onChange={(checked) => this.checkSelect(checked,rowID)} />


