'''iverilog -o fifo.vvp FIFO_test.v'''

'''iverilog -o fifo2.vvp FIFO_test.v'''

''''vvp fifo2.vvp -lx2 > run.log'''

'''gtkwave dump.lx2'''
