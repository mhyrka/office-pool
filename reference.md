import React, { Component } from 'react';
import { AppRegistry, ScrollView, Image, Text, StyleSheet } from 'react-native';




export default class IScrolledDownAndWhatHappenedNextShockedMe extends Component {


  render() {
      return (
        <ScrollView style={{flexDirection: 'column'}}>
          <Text style={{fontSize:96}}>Scroll me plz</Text>
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />

          <Text style={{fontSize:96}}>If you like</Text>
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />

          <Text style={{fontSize:96}}>Scrolling down</Text>
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />

          <Text style={{fontSize:96}}>Whats the best</Text>
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />

          <Text style={{fontSize:96}}>Framework around?</Text>
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />
          <Image source={require('./publicImage.jpg')} resizeMode={'stretch'} style={{ height: 300, width: '100%' }} />

          <Text style={{fontSize:80}}>React Native</Text>
        </ScrollView>
    );
  }
}
