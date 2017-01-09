<template>
    <div>
        <doc-basic :items="items"></doc-basic>
    </div>
</template>

<script>
import DocBasic from '../components/DocBasic'
import items    from './items/getting-started'

export default 
{
    components: 
    {
        DocBasic
    },
    data()
    {
        return { items: items }        
    },
    beforeCreate()
    {
        document.title = 'Getting Started | Tocas UI'
    }
}
</script>