# Information about useForm Hook
Example of use:
```
const initialState = {
    name: '',
    age: 0,
    email: ''
};
const { formValues, handleInputChange, reset } = useForm( initialState );
```