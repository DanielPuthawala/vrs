**Computational Definition**

A simple integer value as a VRS class.

**Information Model**

.. list-table::
   :class: clean-wrap
   :header-rows: 1
   :align: left
   :widths: auto
   
   *  - Field
      - Type
      - Limits
      - Description
   *  - type
      - string
      - 1..1
      - MUST be "Number"
   *  - value
      - integer
      - 1..1
      - The value represented by Number
   *  - color
      - string
      - 1..1
      - The color of the Number.  Eg 42 is mauve and 63 is azure.
