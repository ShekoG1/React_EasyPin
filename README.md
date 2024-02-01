# react-pin-input

A customizable PIN input component for React apps.  


## Introduction

`react-pin-input` provides an easy way to add a PIN code input to your React app. It displays an array of number inputs as circles for entering a PIN.  


### Features

- Automatically focuses inputs and moves caret as PIN is entered   
- Disables used inputs and enables next input
- Backspace/Delete functionality to go back an input  
- Custom submit button and submit handler
- Flexbox based responsive design
- Customizable number of inputs
- Row or column layout


## Usage

Install from npm:

```bash  
npm install react-pin-input  
```

Basic usage:

```jsx  
import PinInput from 'react-pin-input';  

function App() {  

  const handleSubmit = (pin) => {
    console.log(pin);  
  }  

  return (  
    <PinInput    
      pinCount={4}
      autoSubmit={true}  
      OnSubmit={handleSubmit}  
    />  
  );  
}  
```  


## Props

The component accepts the following props:

- **pinCount**: Number of input circles to display  
- **autoSubmit**: Automatically call submit handler if PIN fully entered  
- **OnSubmit**: Function called with entered PIN on submit  
- **submitBtn**: React element for custom submit button   
- **flexDirection**: 'row' or 'column' layout  


## License  

MIT

**Thankyou for viewing. Have a lovely day ahead!**

## Authors

- Made with &#x2764; by **[Shekhar Maharaj]('https://www.theshekharmaharaj.com')**

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.theshekharmaharaj.com)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/the-shekhar-maharaj/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/therealsheko)

*'Making dreams come true'*