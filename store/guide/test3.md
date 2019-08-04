---
layout: post
title: 'H2O theme for Jekyll'
subtitle: 'test'
date: 2017-04-18
categories: test
cover: '/store/img/20190803/colorado.jpg'
tags: jekyll 
---

```js
Basic Methods
Prefix	Method
import moduleName from 'module' //imp→
import 'module' //imn→
import { destructuredModule } from 'module' //imd→
import * as alias from 'module' //ime→
import { originalName as aliasName} from 'module' //ima→
export default moduleName //exp→
export { destructuredModule } from 'module' //exd→
export { originalName as aliasName} from 'module' //exa→
export const functionName = (params) => { } //enf→
export default (params) => { } //edf→
methodName = (params) => { } //met→
arrayName.forEach(element => { } //fre→
for(let itemName of objectName { } //**fof→**
for(let itemName in objectName { } //fin→
(params) => { } a//nfn→
const functionName = (params) => { } //nfn→
const {propName} = objectToDescruct //dob→
const [propName] = arrayToDescruct //dar→
setInterval(() => { }, intervalTime //sti→
setTimeout(() => { }, delayTime //sto→
return new Promise((resolve, reject) => { } p//rom→
comment block c//mmb→
const { } = this.props// cp→
const { } = this.state// cs→
```

```js
React
Prefix	Method
import React from 'react' //imr→
import ReactDOM from 'react-dom' i//mrd→
import React, { Component } from 'react' i//mrc→
import React, { Component } from 'react' & import PropTypes from 'prop-types' im//rcp→
import React, { PureComponent } from 'react' im//rpc→
import React, { PureComponent } from 'react' & import PropTypes from  imr//pcp→'prop-types'
import React, { memo } from 'react' i//mrm→
import React, { memo } from 'react' & import PropTypes from 'prop-types' im//rmp→
import PropTypes from 'prop-types' i//mpt→
import { BrowserRouter as Router, Route, Link } from 'react-router-dom' i//mrr→
import { connect } from 'react-redux' re//dux→
constructor(props) with this.state rco//nst→
constructor(props, context) with this.state rc//onc→
this.state = { } //est→
componentWillMount = () => { } DEPRECATED!!! //cwm→
componentDidMount = () => { } //cdm→
componentWillReceiveProps = (nextProps) => { } DEPRECATED!!! //cwr→
shouldComponentUpdate = (nextProps, nextState) => { } //scu→
componentWillUpdate = (nextProps, nextState) => { } DEPRECATED!!! c//wup→
componentDidUpdate = (prevProps, prevState) => { } c//dup→
componentWillUnmount = () => { } c//wun→
static getDerivedStateFromProps(nextProps, prevState) { } gd//sfp→
getSnapshotBeforeUpdate = (prevProps, prevState) => { } g//sbu→
render() { return( ) } //ren→
this.setState({ }) //sst→
this.setState((state, props) => return { }) //ssf→
this.props.propName pr//ops→
this.state.stateName st//ate→
const ${1:contextName} = React.createContext() rcont//ext→
this.${1:refName}Ref = React.createRef() c//ref→
const ref = React.createRef() f//ref→
this.methodName = this.methodName.bind(this) //bnd→
React Hooks
All hooks from official docs are added with hook name prefix.
React Native
Prefix	Method
import { $1 } from 'react-native' i//mrn→
const styles = StyleSheet.create({}) rnst//yle→
Redux
Prefix	Method
redux action template rxact//ion→
export const $1 = '$1' rxco//nst→
redux reducer template rxredu//cer→
redux selector template rxsel//ect→
PropTypes
Prefix	Method
PropTypes.array //pta→
PropTypes.array.isRequired p//tar→
PropTypes.bool //ptb→
PropTypes.bool.isRequired p//tbr→
PropTypes.func //ptf→
PropTypes.func.isRequired p//tfr→
PropTypes.number //ptn→
PropTypes.number.isRequired p//tnr→
PropTypes.object //pto→
PropTypes.object.isRequired p//tor→
PropTypes.string //pts→
PropTypes.string.isRequired p//tsr→
PropTypes.node p//tnd→
PropTypes.node.isRequired pt//ndr→
PropTypes.element p//tel→
PropTypes.element.isRequired pt//elr→
PropTypes.instanceOf(name) //pti→
PropTypes.instanceOf(name).isRequired p//tir→
PropTypes.oneOf([name]) //pte→
PropTypes.oneOf([name]).isRequired p//ter→
PropTypes.oneOfType([name]) p//tet→
PropTypes.oneOfType([name]).isRequired pt//etr→
PropTypes.arrayOf(name) p//tao→
PropTypes.arrayOf(name).isRequired pt//aor→
PropTypes.objectOf(name) p//too→
PropTypes.objectOf(name).isRequired pt//oor→
PropTypes.shape({ }) p//tsh→
PropTypes.shape({ }).isRequired pt//shr→
PropTypes.any pt//any→
static propTypes = {} pty//pes→
GraphQL
import { compose, graphql } from 'react-apollo'| |grap//hql→

expgql
export default compose(graphql($1, { name: $2 }))($3)
Console
Prefix	Method
console.log(object) //clg→
console.log("object", object) //clo→
console.time("timeId") //ctm→
console.timeEnd("timeId") //cte→
console.assert(expression,object) //cas→
console.clear() //ccl→
console.count(label) //cco→
console.dir //cdi→
console.error(object) //cer→
console.group(label) //cgr→
console.groupEnd() //cge→
console.trace(object) //ctr→
console.warn //cwa→
console.info //cin→
```