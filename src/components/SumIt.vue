<template>
  <p>
    Ukupan zbroj iznosi {{ parseInt(n1) + parseInt(n2) }}
  </p>
</template>

<script>
export default {
  name: 'SumIt',
  props: ['n1', 'n2']
}
</script>