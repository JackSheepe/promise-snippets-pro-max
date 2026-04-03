# Promise snippets

## JavaScript

| Trigger  		| Content                                            																																												 |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------ |
| promise  		| `new Promise((resolve, reject) => { ... });`       																																												 |
| promisef 		| `new Promise(function (resolve, reject) { ... });` 																																												 |
| promisetc 	| `new Promise((resolve, reject) => { ... }).then((result) => { ... }).catch((error) => { ... });` 												 									 |
| promisec 		| `const promise = new Promise((resolve, reject) => { ... });promise.then((result) => { ... }).catch((error) => { ... });` 									 |
| promisefull | `new Promise((resolve, reject) => {... resolve();reject();}).then((result) => { ... }).catch((error) => { ... });` 			 									 |
| promisea 		| `async function promise() {try {let result; ... return result;} catch (error) {... throw error;}};` 						 													 |
| promiseaa 	| `const promise = async () => {try {let result; ... return result;} catch (error) {... throw error;}};` 				 														 |
																																												 
## TypeScript / JavaScript React / TypeScript React

| Trigger 		| Content                                      			 																																												 |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------------------ |
| promise  		| `new Promise((resolve, reject) => { ... });`       																																												 |
| promisef 		| `new Promise(function (resolve, reject) { ... });` 																																												 |
| promisetc 	| `new Promise((resolve, reject) => { ... }).then((result: any) => { ... }).catch((error: Error \| any) => { ... });` 											 |
| promisec 		| `const promise = new Promise((resolve, reject) => { ... });promise.then((result: any) => { ... }).catch((error: Error \| any) => { ... });`|
| promisefull | `new Promise((resolve, reject) => {... resolve();reject();}).then((result: any) => { ... }).catch((error: Error \| any) => { ... });` 		 |
| promisea 		| `async function promise(): Promise<any> {try {let result; ... return result;} catch (error: Error \| any) {... throw error;}};` 					 |
| promiseaa 	| `const promise = async (): Promise<any> => {try {let result; ... return result;} catch (error: Error \| any) {... throw error;}};` 				 |
