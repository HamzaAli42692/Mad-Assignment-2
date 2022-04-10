import { StatusBar } from "expo-status-bar";
import React, { useState } from "react";
import {
  StyleSheet,
  Text,
  View,
  Image,
  TextInput,
  Button,
  TouchableOpacity,
} from "react-native";
 
export default function App() {
  const [email, setEmail] = useState("");
  const [password, setPassword] = useState("");
 
  return (
    <View style={styles.container}>
      <Image style={styles.image} source={require("./assets/Ilogo.png")} />
 
      <StatusBar style="auto" />
      <View style={styles.inputView}>
        <TextInput
          style={styles.TextInput}
          placeholder="Email."
          placeholderTextColor="#003f5c"
          onChangeText={(email) => setEmail(email)}
        />
      </View>
 
      <View style={styles.inputView}>
        <TextInput
          style={styles.TextInput}
          placeholder="Password."
          placeholderTextColor="#003f5c"
          secureTextEntry={true}
          onChangeText={(password) => setPassword(password)}
        />
      </View>
 
      <TouchableOpacity style={styles.loginBtn}>
        <Text style={styles.loginText}>LOGIN</Text>
      </TouchableOpacity>
    
      <View style={{flex: 1, flexDirection: 'row'}}>
             <Text style={styles.l}>________</Text>
             <Text style={styles.p2}> OR </Text>
             <Text style={styles.l}>________</Text>
           </View>
           <Image style={styles.img2} source={require("./assets/fb.png")}/>
    
      
           <TouchableOpacity>
        <Text style={styles.forgot_button}>Forgot Password?</Text>
      </TouchableOpacity>
      
    </View>


    
  );
}
 
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: 'white',
    alignItems: 'center',
    justifyContent: 'center',
    marginLeft: 550,
    marginRight: 550,
    marginTop: 5,
    marginBottom: 10,
    borderWidth: 1,
    height:44,
    borderColor: '#fff',
    marginTop:150,
    marginBottom:60,
    borderColor:'black',
    width:375
  },
 
  image: {
    marginTop:50,
    marginBottom: 30,
    height:60,
    width:200
  },
 
  inputView: {
    marginTop:20,
    width: 300,
    height: 40,
    marginBottom: 10,
    marginTop:10,
fontSize:14,
    color:'#FAFAFA',
  marginLeft:10,
  borderRadius:5
  },
 
  TextInput: {
    fontSize:14,
    height: 40,
    flex: 1,
    paddingLeft:5,
    color:'#FAFAFA',
    backgroundColor:'#FAF9F6',
    borderColor:'#C0C0C0',
borderRadius:4
    
  },
 
  forgot_button: {
    marginBottom:60,
    height: 30,
    marginBottom:10,
    fontSize:12
  },
 
  loginBtn: {
    width: 300,
    height: 30,
    alignItems: "center",
    justifyContent: "center",
    backgroundColor: "#B2DFFC",
    borderRadius:5,
    marginBottom:3
  },
  l:{
    color:'#C0C0C0',
    fontWeight:'bold',
    fontSize:15,
    marginLeft:15
  },
  p2:
  {
    marginTop:10,
    fontSize:14,
    textAlign:'center',
    paddingLeft:5
  },

 img2:{ marginBottom:20,
    height:30,
    width:200},
})
