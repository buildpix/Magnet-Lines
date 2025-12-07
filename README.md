# Magnet Lines

A grid of lines that rotate to point towards the cursor, creating a magnetic field effect.

## Installs

No external dependencies.

## Usage

```jsx
import MagnetLines from './MagnetLines';

const Example = () => {
  return (
    <MagnetLines 
      rows={9}
      columns={9}
      containerSize="300px"
      lineColor="tomato"
      lineWidth="2px"
      lineHeight="20px"
      baseAngle={0}
    />
  );
};

export default Example;
```

## Props

| Prop | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `rows` | `number` | `9` | Number of rows in the grid. |
| `columns` | `number` | `9` | Number of columns in the grid. |
| `containerSize` | `string` | `'80vmin'` | CSS width/height of the container. |
| `lineColor` | `string` | `'#efefef'` | Color of the lines. |
| `lineWidth` | `string` | `'1vmin'` | Width of each line. |
| `lineHeight` | `string` | `'6vmin'` | Height of each line. |
| `baseAngle` | `number` | `-10` | Initial rotation angle. |
| `style` | `object` | `{}` | Inline styles for container. |
