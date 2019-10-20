# styled-components-cheatsheet

### Background Image

```jsx
const BackgroundImage = styled.div`
  background-size: contain;
  background-repeat: no-repeat;
  background-position: 50%;
  background-image: url(${({ image }) => image });
  width: ${({ width }) => width };
  height: ${({ height }) => height };
`;
```
