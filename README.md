# rn-elemets-snippets README

React-native UI lib , React Native Elements is quite popular in development world and visual studio code is prefered editor.
So this is the lib which will provide the snippets from which Elements can be created by just typing shortest word possible.
## Features
Snippets command availables are as below.

`rne-avatar-simple`

```
    <Avatar
        title="RN"
    />
```

`rne-avatar-rounded`

```
    <Avatar
        rounded
        title="RN"
    />
```

`rne-avatar-img`

```
    <Avatar
        rounded
        source={{uri:"https://s3.amazonaws.com/uifaces/faces/twitter/ladylexy/128.jpg"}}
    />
```

`rne-avatar-icon`

```
    <Avatar
        rounded
        icon={{name:"home"}}
    />
```

`rne-avatar-badge`

```
    <View>
        <Avatar
            rounded
            showEditButton
            onEditPress={ _ => alert("Edit Pressed.")}
            source={{uri:"https://s3.amazonaws.com/uifaces/faces/twitter/ladylexy/128.jpg"}}
        />
        <Badge
            status="success"
            containerStyle={{ position: 'absolute', top: -4, right: -4 }}
        />
    </View>    
```

`rne-avatar-edit`

```
    <Avatar
        rounded
        showEditButton
        onEditPress={ _ => alert("Edit Pressed.")}
        source={{uri:"https://s3.amazonaws.com/uifaces/faces/twitter/ladylexy/128.jpg"}}
    />
```

`rne-badge-simple`

```
    <Badge
        value="99+"
        status="error"
    />
```

`rne-badge-text`

```
    <Badge
        value={<Text>RN</Text>}
        status="error"
    />
```

`rne-badge-success`

```
    <Badge
        status="success"
    />
```

`rne-badge-error`

```
    <Badge
        status="error"
    />
```

`rne-badge-warning`

```
    <Badge
        status="warning"
    />
```

`rne-badge-primary`

```
    <Badge
        status="parimary"
    />
```

`rne-button`

```
    <Button
        //raised
        //loading
        //loadingProps http://reactnative.dev/docs/activityindicator#props
        //disabled
        //disabledStyle
        title="Title"
        titleStyle={{}}
        onPress={_=> alert('Button Pressed.')}
    />
```

`rne-button-outline`

```
    <Button
        //raised
        //loading
        //loadingProps http://reactnative.dev/docs/activityindicator#props
        //disabled
        //disabledStyle
        title="Title"
        titleStyle={{}}
        type="outline"
        onPress={_=> alert('Button Pressed.')}
    />
```

`rne-button-clear`

```
    <Button
        //raised
        //loading
        //loadingProps http://reactnative.dev/docs/activityindicator#props
        //disabled
        //disabledStyle
        title="Title"
        titleStyle={{}}
        type="clear"
        onPress={_=> alert('Button Pressed.')}
    />
```

`rne-button-icon`

```
    <Button
        icon={{name:"home"}}
        //raised
        //loading
        //loadingProps http://reactnative.dev/docs/activityindicator#props
        //disabled
        //disabledStyle
        title="Title"
        titleStyle={{}}
        type="clear" //options(solid, clear, outline)
        onPress={_=> alert('Button Pressed.')}
    />
```

`rne-card`

```
    <Card
        title="Card Title"
        containerStyle={{}}
        dividerStyle={{}}
        wrapperStyle={{}}
    >
    </Card>
```

`rne-card-image`

```
    <Card
        title="Card Title"
        containerStyle={{}}
        dividerStyle={{}}
        featuredTitle="featured" // if image props given
        featuredTitleStyle={{}} // if image props given
        featuredSubtitle="featured" // if image props given
        featuredSubtitleStyle={{}} // if image props given
        image={} //uri or require path
        imageStyle={{}}
        imageWrapperStyle={{}}
        wrapperStyle={{}}
    >
    </Card>
```

`rne-checkbox`

```
    <CheckBox
        left
        //right
        //center
        title="Click Me."
        //checkedColor="" default is green
        //checkedIcon="" default is check-square-o
        //uncheckedIcon="" default is square-o
        //uncheckedColor="" default is #bfbfbf
        //checkedTitle=""
        checked={true} // maintain it with state
        onPress={_=> alert('Checkbox clicked, here have to maintain state.')}
    />
```

`rne-divider`

```
    <Divider
        style={{}}
    />
```

`rne-header`

```
    <Header
        placement="center" // options ('left', 'center' or 'right') 
        //containerStyle={{}}
        backgroundColor=""
        leftComponent={{ icon: 'menu', color: '#fff' }} // this could be text string, any react component
        centerComponent={{ text: 'MY TITLE', style: { color: '#fff' } }} // this could be text string, any react component
        rightComponent={{ icon: 'home', color: '#fff' }} // this could be text string, any react component
        barStyle="default" //options ('default', 'light-content', 'dark-content')
        //statusBarProps={} // http://reactnative.dev/docs/statusbar.html#props
    />
```

`rne-header-img`

```
    <Header
        placement="center" // options ('left', 'center' or 'right') 
        //containerStyle={{}}
        //backgroundImage={{}}
        //backgroundImageStyle={{}}
        backgroundColor=""
        leftComponent={{ icon: 'menu', color: '#fff' }} // this could be text string, any react component
        centerComponent={{ text: 'MY TITLE', style: { color: '#fff' } }} // this could be text string, any react component
        rightComponent={{ icon: 'home', color: '#fff' }} // this could be text string, any react component
        barStyle="default" //options ('default', 'light-content', 'dark-content')
        //statusBarProps={} // http://reactnative.dev/docs/statusbar.html#props
    />
```

`rne-icon`

```
    <Icon
        type="material" //options ('material-community', 'font-awesome', 'octicon', 'ionicon', 'foundation', 'evilicon', 'simple-line-icon', 'zocial', 'entypo', 'feather', 'antdesign')
        name="rowing"
        size={26}
        iconStyle={{}}
        color="black"
        //disabled
        //reverse
        //raised
        onPress={_=> alert('Icon Pressed!')}
    />
```

`rne-img`

```
    <Image
        style={{ width: 200, height: 200 }}
        source={{ uri: '' }}
        PlaceholderContent={<ActivityIndicator />}
        //containerStyle={{}}
    />
```

`rne-input`

```
    <Input
        placeholder={'Enter Something'}
        label={'Enter Something'}
        inputContainerStyle={{}}
        inputStyle={{}}
        //containerStyle={{}}
        //disabled
        //disabledInputStyle={{}}
        errorMessage={''}
        //errorStyle={{}}
    />
```

`rne-input-icon-r`

```
    <Input
        rightIcon={{name:'home'}}
        rightIconContainerStyle={{}}
        placeholder={'Enter Something'}
        label={'Enter Something'}
        inputContainerStyle={{}}
        inputStyle={{}}
        //containerStyle={{}}
        //disabled
        //disabledInputStyle={{}}
        errorMessage={''}
        //errorStyle={{}}
    />
```

`rne-input-icon-l`

```
    <Input
        leftIcon={{name:'home'}}
        leftIconContainerStyle={{}}
        placeholder={'Enter Something'}
        label={'Enter Something'}
        inputContainerStyle={{}}
        inputStyle={{}}
        //containerStyle={{}}
        //disabled
        //disabledInputStyle={{}}
        errorMessage={''}
        //errorStyle={{}}
    />
```

`rne-list-item`

```
    <ListItem
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-icon-l`

```
    <ListItem
        leftIcon={{name:'home'}}
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-icon-r`

``` 
    <ListItem
        rightIcon={{name:'home'}}
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-avatar-l`

```
    <ListItem
        leftAvatar={{title:'Title'}} //can have all icon props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-avatar-r`

```
    <ListItem
        rightAvatar={{title:'Title'}} //can have all icon props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-switch`

```
    <ListItem
        switch={{title:'Title'}} //can have all switch props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-input`

```
    <ListItem
        input={{label:'Title'}} //can have all input props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-checkbox`

``` 
    <ListItem
        checkBox={{title:'Title'}} //can have all checkBox props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-list-item-badge`

```
    <ListItem
        badge={{value:'Title'}} //can have all badge props
        title={'Title'}
        //titleStyle={{}}
        subtitle={'Sub Title'}
        //subtitleStyle={{}}
        //containerStyle={{}}
        //bottomDivider
        //chevron
        //checkmark
        onPress={_=> alert('List Item Pressed!.')}
    />
```

`rne-modal`

```
    <Overlay
        isVisible={false} //manage this with state
        overlayBackgroundColor={'white'}
        windowBackgroundColor={'rgba(0, 0, 0, .5)'}
        onBackdropPress={_=> alert('Backdrop Pressed!.')}
        //overlayStyle={{}}
        //containerStyle={{}}
        //borderRadius={3}
        //children={null} // React Native Component
        //fullScreen
        //height={100} // default is window height - 180
        //width={100} // default is window width - 80
    >
        <Text>Modal Body</Text>
    </Overlay>
```

`rne-pricing`

```
    <PricingCard
        price={'100'}
        title={'Title'}
        button={{title: 'Buy', icon: 'home', buttonStyle:{}, titleStyle:{}}}
        onButtonPress={_ => alert('Buttoon Pressed!')}
        info={['Feature 1', 'Feature 2']}
        //color={''}
        //infoStyle={{}}
        //containerStyle={{}}
        //pricingStyle={{}}
        //titleStyle={{}}
        //wrapperStyle={{}}
    />
```

`rne-search`

```
    <SearchBar
        placeholder='search ...'
        placeholderTextColor={'#86939e'}
        onChangeText={keyword=> this.setState({keyword})}
        onClear={_=> this.setState({keyword: ''})}
        onCancel={_=> this.setState({keyword: ''})}
        platform='default' // options(ios / android) 
        underlineColorAndroid='transparent'
        //round // if platform is default
        //showLoading
        //clearIcon={{ name: 'home' }}
        //searchIcon={{ name: 'home' }}
        //cancelIcon={{ name: 'home' }} // android only
        //containerStyle={{}}
        //inputContainerStyle={{}}
        //inputStyle={{}}
        //leftIconContainerStyle={{}}
        //rightIconContainerStyle={{}}
    />
```

`rne-tile`

```
    <Tile
        imageSrc={{uri:''}}
        title='Title'
        titleStyle={{}}
        featured={false}
        caption={'Captions'}
        captionStyle={{}}
        containerStyle={{}}
        icon={{ name: 'play-circle', type: 'font-awesome' }}
        iconContainerStyle={{}}
        imageContainerStyle={{}}
        onPress={_=> alert('Tile Pressed!')}
        activeOpacity={0.2}
        //height={100} // default Device Width * 0.8
        //width={100} // default Device Width
    />
```

`rne-tooltip`

```
    <Tooltip
        popover={<Text>Info here</Text>} // React Component
        backgroundColor={'#617080'}
        height={40}
        width={150}
        highlightColor={'transparent'}
        onClose={_ => {}}
        onOpen={_ => {}}
        overlayColor={'rgba(250, 250, 250, 0.70)'}
        toggleOnPress={true}
        withOverlay={true}
        withPointer={true}
        containerStyle={{}}
    >
        <Text>Press me</Text>
    </Tooltip>
```

## Requirements
You need to have this lib installed as dependency in project.
    `https://react-native-elements.github.io/react-native-elements/`
Have to import the Element which you are creating using snippets.

**Enjoy!**
