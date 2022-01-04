# 01/03 Monday 5:04pm <br/>

### TITLE : Happpy New Year! and Let's code!\*\* <br/>

### TYPE: TIL

| <!-- -->          | <!-- -->                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CASE              | I have read the RN tutorial book occidently, and found why immutability is important in react. I knew why but I could have known earlier if I have read the tutorial right when I bought the textbook in 2019.                                                                                                                                                                                                                                                                                |
| WHAT I HAVE LEARN | I should be more diligent in 2022, and try to finish readng textbooks ASAP. The reason why react should keep immutability is because of the way of rendering with optimization. In react, when parent component has to update, then it's children component has to rerender. And to know when it should rerender is when there is a change in Props. Therefore, in order to compare previous object and upcoming object, we need to make sure objects that we are comparing are not the same. |

# 01/04 Tuesday 21:28pm <br/>

### TITLE : Error Handling in React Native <br/>

### TYPE: TIL

| <!-- -->          | <!-- -->                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CASE              | As a react native developer, shipping a new application with a high percentage bugs-free could be challenging. We need to learn how to deal with unthought errors.                                                                                                                                                                                                                                                                                                                                                                             |
| WHAT I HAVE LEARN | type 1. typescript will help you avoid all errors caused by typos and typing errors <br/> type 2. write higher coverage tests for your app <br/> type 3. try/catch is great but it only works for imperative code <br/> type 4. React components are declarative. Error boundaries are React components that catch JavaScript errors anywhere in the child component tree. Recommend React-error-boundary Library <br/> type 5. (Optional) Use Sentry, cloud-based error monitoring platform that helps us track all these errors in real-time |

Reference

https://elazizi.com/handling-errors-in-react-native-a-complete-guide
https://reactjs.org/docs/error-boundaries.html
