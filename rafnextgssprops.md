# Snippet content:
```JSX
// You should use getServerSideProps when:
// - Only if you need to pre-render a page whose data must be fetched at request time

export const getServerSideProps: GetServerSideProps = async ({ ctx }) => {
    
    const { data } = await;

    return {
        props: {
            
        }
    }
}
```
