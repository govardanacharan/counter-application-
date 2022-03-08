![image](https://user-images.githubusercontent.com/95639773/157197469-5525ca17-90b1-4d1f-9bfa-e527fe6f7316.png)
import React from 'react';
import { StyleSheet, Text, View } from 'react-native';

import CountContextProvider from './context/CountContextProvider';
import MainScreen from './components/Mainscreen';
import TopView from './components/TopView';
import Bottom from './components/botoom';
export default function App() {
  return (
   
   <CountContextProvider>
    <MainScreen/>
    <TopView></TopView>
    <Bottom></Bottom>
   </CountContextProvider>
   
  
  );
}
