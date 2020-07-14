# Redux - Additional Topics

## Redux Toolkit

- The makers of Redux have recognized that Redux is complicated and have introduced a “Batteries Included, Highly Opinionated” framework for making stores called the Redux Toolkit

- This toolkit specifies a few different means of building a reducer and action set that work well together and are easier to understand and integrate

- Ultimately, your store code can be as simple and declarative as this:

```javascript

const postsSlice = createSlice({ name: ‘posts’, initialState: [], reducers: { createPost(state, action) {}, updatePost(state, action) {}, deletePost(state, action) {} } })

- Extract the action creators object and the reducer
const { actions, reducer } = postsSlice () Extract and export each action creator by name)
 export const { createPost, updatePost, deletePost } = actions 
 - Export the reducer, either as a default or named export export default reducer

 ————— Sample Use ————– 
  console.log(createPost({ id: 123, title: ‘Hello World’ })) 
   {type : “posts/createPost”, payload : {id : 123, title : “Hello World”}}

 Notice how createSlice transforms your defiition?
  console.log(postsSlice)  { name: ‘posts’, actions : { createPost, updatePost, deletePost, }, reducer } 