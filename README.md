# datagridviewproperties
properties to allow visibly easy to read dgv

dataGridView1.Rows.Clear();
            dataGridView1.Columns.Clear();
            dataGridView1.CurrentCell = null; // set current cell to null
            dataGridView1.ColumnCount = 24;
            dataGridView1.RowCount = 3; 
            dataGridView1.SelectionMode = DataGridViewSelectionMode.CellSelect;
            dataGridView1.AutoSizeColumnsMode = DataGridViewAutoSizeColumnsMode.Fill;
