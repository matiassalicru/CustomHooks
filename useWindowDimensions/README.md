# Cómo usar este hook ?


```const Component = () => {
  const { height, width } = useWindowDimensions(); // Esto es lo importante

  return (
    <div>
      width: {width} ~ height: {height}
    </div>
  );
}
```
