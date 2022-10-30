# What to know to do

# Crud
1- NextJS

2- ReactJS

3- ElectronJS

4- Django

5- React Native
- Curso Udemy login : https://github.com/expo-spain/udemy-birthday/tree/58ca14a6583110d6a3ecce1497b161f101c8824f [Firebase]

# Auth

# Pagination

# Theme

# Print PDF

# Cron

# Upload Files

# Deploy

# API

5- React Native
- API REST Curso Youtube : https://github.com/expo-spain/react-native-coingecko/blob/main/App.js

# i18n

# DB
5- React Native
- https://github.com/expo-spain/youtube-async-storage/blob/main/App.js [ async-storage ]

# CSS for react Native
## TextInput
```
 <TextInput style={[styles.input, styles.error]}
            placeholder="Name"
            placeholderTextColor="#969696"
            autoCapitalize='none'
            onChange={(e) => setName( e.nativeEvent.text)}
      />
      
      
input : {
  height: 50,
  color: '#fff',
  width: '80%',
  marginBottom: 25,
  backgroundColor: '#1e3040',
  paddingHorizontal: 20,
  borderRadius: 50,
  fontSize: 18,
  borderWidth: 1,
  borderColor: '#1e3040'
},
 ```
 
 # Library
 5- React Native

 - https://styled-components.com/
 ```
 import styled from 'styled-components/native';


  export default function App() {
  return (
    <Container>
      <Text>Open up App.js to start working on your app!</Text>
    </Container>
  );
  }
 
  const Container = styled.View`
  flex: 1;
  background-color: white;
  align-items: center;
  justify-content: center;
`;


const Text = styled.Text`
  font-size: 18px;
  color: blue;
  font-weight: 500;
`;
  ```
  
  ```
  import React from 'react';
import styled from 'styled-components/native';
const ButtonContainer = styled.TouchableOpacity`
  margin-vertical: 40px;
  width: 120px;
  height: 40px;
  padding: 12px;
  border-radius: 10px;
  background-color: ${props => props.bgColor};
`;
const ButtonText = styled.Text`
  font-size: 16px;
  text-align: center;
`;
const PressableButton = ({ onPress, bgColor, title }) => (
  <ButtonContainer onPress={onPress} bgColor={bgColor}>
    <ButtonText>{title}</ButtonText>
  </ButtonContainer>
);
export default PressableButton;
  
  ```
 - https://akveo.github.io/react-native-ui-kitten/


