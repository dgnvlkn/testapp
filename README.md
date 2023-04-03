<h1>Memorial Mobile Application</h1>
<hr><p>Memorial application has been developed to ensure a quick access to both Memorial healtcare services and your personal health data. You can also reach out to Memorial Home Healthcare Services easily online</p><h2>General Information</h2>
<hr><ul>
<li>Memorial application has been developed to ensure a quick access to both Memorial healtcare services and your personal health data. You can also reach out to Memorial Home Healthcare Services easily online</li>
</ul>
<p>Firebase Application Name:
memorial-app-40b05</p><h2>Technologies Used</h2>
<hr><ul>
<li>JavaScript</li>
</ul><ul>
<li>React</li>
</ul><h2>Features</h2>
<hr><ul>
<li>Firebase</li>
</ul><h2>Screenshots</h2>
<hr><p><img src="https://is4-ssl.mzstatic.com/image/thumb/PurpleSource122/v4/b4/a5/be/b4a5bea2-dba6-8953-de05-db0be63b2c0a/def3cd15-0627-4b8c-9381-771fd8b22206_ios_6.5__U00282_U0029.png/460x0w.webp" alt=""></p><p><img src="https://is4-ssl.mzstatic.com/image/thumb/PurpleSource112/v4/3c/63/d6/3c63d638-9bc4-7e29-61ea-f94058ea59f6/c2320ff8-9521-4c1b-9474-86276211b5a5_ios_6.5-1.png/460x0w.webp" alt=""></p><p><img src="https://is3-ssl.mzstatic.com/image/thumb/PurpleSource122/v4/65/e8/5c/65e85ca1-03f5-dd37-73f9-a9903c7aec66/078d6ed9-647e-4c56-9d71-34059a985637_ios_6.5-6.png/460x0w.webp" alt=""></p><p><img src="https://is4-ssl.mzstatic.com/image/thumb/PurpleSource112/v4/1d/6f/07/1d6f0704-4f32-766e-109a-7420526a149f/ac9f3f4f-da92-4ec0-b11a-63aa4fc8b004_ios_6.5-2.png/460x0w.webp" alt=""></p><h5>Steps</h5><ul>
<li>yarn install</li>
</ul><ul>
<li>yarn android</li>
</ul><ul>
<li>yarn ios</li>
</ul><h5>Code Examples</h5><ul>
<li>redux</li>
</ul><p><code> const dispatch = useDispatch(); dispatch(       actionLogin(         {           tip: state.noTypeId,           kimlikNo: state.identification_number,           dogumTarihi,         },         cb,       ),     );</code></p><ul>
<li>network example</li>
</ul><p><code>const actionSetDevice = (   payload: loginRequestProps,   callback?: ({ type, payload }: requestCallback) =&gt; void, ): requestActionProps =&gt; ({   type: requestGenerate(Types.LOGIN),   payload: { data: payload },   api: api.login,   callback,   isQueue: true, });</code></p><ul>
<li>axios config</li>
</ul><p><code>const config: AxiosRequestConfig = {   baseURL,   headers: {     'Content-Type': 'application/json',     'deviceModel': deviceModel,     'deviceBrand': deviceBrand,     'deviceOS': Platform.OS,     'os': Platform.OS,     'model': deviceModel   }, };</code></p><ul>
<li>api address config</li>
</ul><p><code>const MAIN_REQUEST_URL = 'https://mmapi.memorial.com.tr'</code></p><ul>
<li>translate config</li>
</ul><p><code>const SUPPORTED_LANGUAGES = ['tr', 'en']; const DEFAULT_LANGUAGE = 'tr'; const I18NEXT_DEBUG = false; const FALLBACK_LANGUAGE = 'tr'; const ACTIVE_TRANSLATION = true;</code></p><ul>
<li>translate example</li>
</ul><p><code> const { t } = useTranslation();</code></p><ul>
<li>style example</li>
</ul><p><code>import { StyleSheet, ViewStyle } from 'react-native'; import { themeProps } from '@theme';  type stylesProps = {   screen?: ViewStyle;   headerFooterInner?: ViewStyle;   dropdown?: ViewStyle;   toptab?: ViewStyle;   card?: ViewStyle;   listTab?: ViewStyle;   spaceBetween?: ViewStyle;   row?: ViewStyle;   listTabFooter?: ViewStyle;   maptab?: ViewStyle;   hospitalCardFooter?: ViewStyle;   hospitalCardFooterItem?: ViewStyle;   hospitalCard?: ViewStyle; };  const createStyles = (theme: themeProps) =&gt;   StyleSheet.create&lt;stylesProps&gt;({     screen: {       borderTopWidth: 1,       borderTopColor: theme.color.text.lightGray,     },     headerFooterInner: {       flexDirection: 'row',       justifyContent: 'space-between',       alignItems: 'center',       marginTop: 16,       marginBottom: -10,     },     dropdown: {       flex: 0.46,     },     toptab: {       marginHorizontal: 5,       marginBottom: 7,       marginTop: 20,     },     card: {       backgroundColor: theme.color.text.white,       padding: 14,       borderRadius: 10,       shadowColor: '#000',       shadowOffset: {         width: 0,         height: 2,       },       shadowOpacity: 0.1,       shadowRadius: 4,       elevation: 2,       marginBottom: 24,     },     listTab: {       paddingTop: 16,       paddingHorizontal: 16,     },     spaceBetween: {       flexDirection: 'row',       alignItems: 'center',       justifyContent: 'space-between',     },     row: {       flexDirection: 'row',       alignItems: 'center',       marginBottom: 16,     },     listTabFooter: {       borderTopWidth: 1,       borderTopColor: theme.color.text.lightGray,       marginHorizontal: -16,       paddingHorizontal: 16,       paddingTop: 18,       paddingBottom: 8,     },     hospitalCardFooter: {       flexDirection: 'row',       alignItems: 'center',       justifyContent: 'space-between',     },     hospitalCardFooterItem: {       paddingVertical: 16,       borderTopWidth: 1,       borderTopColor: theme.color.text.lightGray,       borderRightColor: theme.color.text.lightGray,       borderRightWidth: 1,       flex: 1 / 3,       justifyContent: 'center',       alignItems: 'center',     },     hospitalCard: {       backgroundColor: theme.color.text.white,       paddingTop: 14,       borderRadius: 10,       shadowColor: '#000',       shadowOffset: {         width: 0,         height: 2,       },       shadowOpacity: 0.1,       shadowRadius: 4,       elevation: 2,       marginBottom: 24,     },   });  export { createStyles };</code></p>