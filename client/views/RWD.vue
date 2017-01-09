<template>
    <div>
        <doc-basic :items="items"></doc-basic>
    </div>
</template>

<script>
import DocBasic from '../components/DocBasic'
import items    from './items/rwd'

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
        document.title = 'Responsive | Tocas UI'
    }
}
</script>