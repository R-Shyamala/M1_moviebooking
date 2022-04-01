PROJ_NAME = Movie_Ticket_Booking_System


build_test:
	gcc $(TEST_SRC) $(INC) $(INCLUDE_LIBS) -o $(call FixPath,$(PROJ_NAME).$(EXEC)) -lm

run_test: build_test
	./$(call FixPath,$(PROJ_NAME).$(EXEC))

